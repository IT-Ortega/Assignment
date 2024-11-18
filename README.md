public class StringConcatenation {                                          Explanatoin
public static String concatenateStrings(String str1, String str2) {         *ConcatenateString takes two string (str1,str2) as input
int len1 = str1.lenth();                                                     in calculates thir lengths,creates a new character array
int len2 = str2.length();                                                    (str3)large enough to hold both strings,and then copeis str2
 char[] str3 = new char[len1 + len2];                                        into str3 using while loops. Finally it retuns a new from str3
 int i = 0;                                                                 *ConcatenateString it initializes two sample strings, calls
 while (i < len1) {                                                          concatenateStrings to concatenate them,and prints the resukt to console
 str3[i] = str1.charAt(i);
 i++;
 }
 int j = 0;
 while (i < len1 + len2) {
 str3[i] = str2.charAt(j);
 i++
 j++
 }
 return new String(str3[]args) {
 String str1 + "Roumar";
 String str2 = "Ortega";
 String concatenatedString = concatenateStrings(str1, str2);
 System.out.printIn(concatenatedString); //Output: Roumar Ortega
 }
 }
