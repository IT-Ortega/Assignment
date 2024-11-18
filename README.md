public class StringConcatenation {                                          
public static String concatenateStrings(String str1, String str2, String str3) {         
int len1 = str1.lenth();                                                   
int len2 = str2.length();
int len2 = str3.length();
 char[] str3 = new char[len1 + len2 + len3];                                       
 int i = 0;                                                                 
 while (i < len1) {                                                          
 str3[i] = str1.charAt(i);
 i++;
 }
 int j = 0;
 while (i < len1 + len2 + len3) {
 str3[i] = str2.charAt(j);
 i++
 j++
 }
 return new String(str3[]args) {
 String str1 = "Roumar";
 String str2 = "Ortega";
 String str3 = "Pasacao";
 String concatenatedString = concatenateStrings(str1, str2, str3);
 System.out.printIn(concatenatedString); //Output: Roumar Ortega Pasacao
 }
 }
