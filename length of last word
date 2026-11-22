int lengthOfLastWord(char* s) {
    int i = strlen(s) - 1;
    int count = 0;

    // Skip trailing spaces
    while (i >= 0 && s[i] == ' ') {
        i--;
    }

    // Count characters in the last word
    while (i >= 0 && s[i] != ' ') {
        count++;
        i--;
    }

    return count;
}
