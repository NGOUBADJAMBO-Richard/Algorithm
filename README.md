# Algorithm

    // Initialize three counters:
    //     length to count the length of the sentence
    //     word_count to count the number of words
    //     vowel_count to count the number of vowels
procedure MyProcedure(sentence);
var
    length, word_count, vowel_count: integer;
begin

    // Read the sentence character by character:
    // Increment length for each character read
    while(length < 100)

        if(sentence[length] != '.')
            length += 1;
        end

    // Determine the number of words:
    // Increment word_count every time a space character is encountered
        if(sentence[length] == ' ')
        word_count += 1
        end

     // Determine the number of vowels:
    //  Check each character against a set of vowels (a, e, i, o, u)
    //  Increment vowel_count for each vowel found
        if(sentence[lenght] == 'aeiou')
        vowel_count += 1
        end
    end
        // Print or return the results:
        // Print the length, word count, and vowel count
        print ("Length of the sentence:", length)
        print("Number of words:", word_count)
        print("Number of vowels:", vowel_count)
end;

