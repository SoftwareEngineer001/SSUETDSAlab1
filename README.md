# SSUETDSAlab1
public class lab1 {
    public static void main(String[] args) {

    int count = 0; 
    String vowels = "aeiouAEIOU"; 
    String str1 = "Software Engineering"; 
    String addedVowel = ""; 
    for (int i = 0; i < str1.length(); i++) { 
        String str2 = String.valueOf(str1.charAt(i)); 
            if (vowels.contains(str2)) { 
                count = count + 1; 
                addedVowel = addedVowel.concat(str2); 
            } 
        } 

    StringBuilder sb = new StringBuilder(addedVowel); 
    String reversedVowel = sb.reverse().toString(); 
    System.out.println("Reversed Vowels: " + reversedVowel);    
    } 
} 
        
        /*Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter a sentence: ");
        String sentence = scanner.nextLine();
        
        String[] words = sentence.split(" "); 
        
        String longestWord = "";
        
        for (String word : words) {
            if (word.length() > longestWord.length()) {
                longestWord = word;
            }
        }
        
        System.out.println("The longest word is: " + longestWord);
        
        scanner.close();
    }
}*/

        /*Scanner scanner = new Scanner(System.in);

        System.out.print("Enter a number: ");
        Double number = scanner.nextDouble(); 

        Double absoluteValue = Math.abs(number); 

        Double squareRoot = number >= 0 ? Math.sqrt(number) : null; 

        System.out.print("Enter the exponent value: ");
        Double exponent = scanner.nextDouble();
        Double power = Math.pow(number, exponent); 

        System.out.println("Absolute value of " + number + ": " + absoluteValue);
        System.out.println("Square root of " + number + ": " + (squareRoot != null ? squareRoot : "Undefined for negative numbers"));
        System.out.println(number + " raised to the power of " + exponent + ": " + power);

        scanner.close();
    }
}
*/
        
        /*Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter an integer: ");
        int number = scanner.nextInt();
        
        Integer num = number;
        
        int evenCount = 0;
        int oddCount = 0;
        
        while (num != 0) {
            int digit = num % 10;
            if (digit % 2 == 0) {
                evenCount++; 
            } else {
                oddCount++;  
            }
            num /= 10;
        }
        
        System.out.println("Number of even digits: " + evenCount);
        System.out.println("Number of odd digits: " + oddCount);
        
        scanner.close();
    }
}*/

      /*  int primitiveInt = 10;
        Integer wrappedInt = primitiveInt;
        double primitiveDouble = 20.5;
        Double wrappedDouble = primitiveDouble;  
        char primitiveChar = 'B';
        Character wrappedChar = primitiveChar;  

        System.out.println("Autoboxed Integer: " + wrappedInt);
        System.out.println("Autoboxed Double: " + wrappedDouble);
        System.out.println("Autoboxed Character: " + wrappedChar);

        System.out.println("\nUsing Wrapper Class Methods:");
        
        System.out.println("Max Integer Value: " + Integer.MAX_VALUE);
        System.out.println("Min Integer Value: " + Integer.MIN_VALUE);

        System.out.println("Double as Integer: " + wrappedDouble.intValue());
        
        System.out.println("Is 'B' a letter? " + Character.isLetter(wrappedChar));
        System.out.println("Lowercase of 'B': " + Character.toLowerCase(wrappedChar));
    }
}
*/
      /*  String word1 = "abc";
        String word2 = "pqr";
        
        String mergedString = "";
        
        int length1 = word1.length();
        int length2 = word2.length();
        
        for (int i = 0; i < Math.max(length1, length2); i++) {
            if (i < length1) {
                mergedString += word1.charAt(i);
            }
            if (i < length2) {
                mergedString += word2.charAt(i); 
            }
        }
        
        System.out.println("Merged string: " + mergedString);
    }
}


  */

        /*
        System.out.println("Integer:");
        System.out.println("Minimum Value: " + Integer.MIN_VALUE);
        System.out.println("Maximum Value: " + Integer.MAX_VALUE);
        
        System.out.println("\nFloat:");
        System.out.println("Minimum Value: " + Float.MIN_VALUE);
        System.out.println("Maximum Value: " + Float.MAX_VALUE);
        
        System.out.println("\nDouble:");
        System.out.println("Minimum Value: " + Double.MIN_VALUE);
        System.out.println("Maximum Value: " + Double.MAX_VALUE);
    }
}      
        /*
        
        
  
        /* String str1 = "My ";
        String str2 = "Name ";
        String str3 = "is ";
        String str4 = "Muhammad ";
        String str5 = "Talha ";

        String concatString = str1 + str2 + str3 + str4 + str5;
        System.out.println("Concatenated String: " + concatString);

        String upperStr4 = str4.toUpperCase();
        System.out.println("Fourth String in Uppercase: " + upperStr4);

        String substring = concatString.substring(11);
        System.out.println("Substring from index 8 onwards: " + substring);
    }
}
        
       */ 
        
  
        
      /*  double primitiveDouble = 3.47;

        Double wrapperDouble = primitiveDouble; 

        System.out.println("Primitive double: " + primitiveDouble);
        System.out.println("Wrapper Double object: " + wrapperDouble);
*/


        
        
      /*  String str1 = "Name: Muhammad Talha";
        
        String str2 = "Name: Muhammad Talha";
        
        String str3 = new String("Dept: Software Engineering");
        
        String str4 = new String("Semester: 3rd semester").intern();
        
        String str5 = "University: SSUET";
        str5 = str5.replace("SSUET","Sir Syed University of Engineering And Technology" );
        
        System.out.println(str1);
        System.out.println(str2);
        System.out.println("string 1 and string 2 are equal"+"("+(str2 == str1)+")");
        System.out.println(str3);
        System.out.println(str4);
        System.out.println(str5);
    }   
}*/








