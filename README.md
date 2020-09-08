# lane_csc250_HW1
class Main {
  public static void main(String[] args) {
    String nt_vowel = "Philippians";
    int vowel_count = 0; 
    for(int i = 0; i < nt_vowel.length(); i += 1) //declare loop variable first; condition is second statement; third statement occurs after i exits the loop //semicolon makes it an empty loop
    {  
      if (nt_vowel.charAt(i) == ('a'))
      {
        vowel_count += 1;
      }
      else if (nt_vowel.charAt(i) == ('e'))
      {
        vowel_count += 1;
      }
      else if (nt_vowel.charAt(i) == ('i'))
      {
        vowel_count += 1;
      }
       else if (nt_vowel.charAt(i) == ('o'))
      {
        vowel_count += 1;
      }
       else if (nt_vowel.charAt(i) == ('u'))
      {
        vowel_count += 1;
      }
       else if (nt_vowel.charAt(i) == ('A'))
      {
        vowel_count += 1;
      }
       else if (nt_vowel.charAt(i) == ('E'))
      {
        vowel_count += 1;
      }
       else if (nt_vowel.charAt(i) == ('I'))
      {
        vowel_count += 1;
      }
       else if (nt_vowel.charAt(i) == ('O'))
      {
        vowel_count += 1;
      }
       else if (nt_vowel.charAt(i) == ('U'))
      {
        vowel_count += 1;
      } 
    }
    System.out.println(vowel_count);
  }
}
//For further practice, do it all in one condition. Write a function that returns a Boolean that asks if it's a vowel or not. If it's a vowel, it will enter the if statement. 

//More practice: Use or statements. If charAt (0) == "A"
