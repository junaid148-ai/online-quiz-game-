#include <iostream>
#include <string>
using namespace std;
int main() 
{
    cout << "This is your quiz " << endl;
    int score = 0;
    char answer;    
    cout << "Question 1" << endl << "How many planets are there in the universe?" << endl;
    string options1[4] = {"a. 8", "b. 9", "c. 12", "d. Unknown"};
    for (int i = 0; i < 4; i++) {
        cout << options1[i] << endl;
    }
    cout << "Your answer (a/b/c/d): ";
    cin >> answer;

    if (answer == 'd') {
        cout << "Correct! +10 points" << endl;
        score += 10;
    } else {
        cout << "Incorrect. The correct answer is d." << endl;
    }
    cout << "Your total score: " << score << endl;

    cout << "Question 2" << endl << "On which planet can we live?" << endl;
    string options2[4] = {"a. Earth", "b. Mars", "c. Jupiter", "d. Unknown"};
    for (int i = 0; i < 4; i++) {
        cout << options2[i] << endl;
    }
    cout << "Your answer (a/b/c/d): ";
    cin >> answer;

    if (answer == 'a') {
        cout << "Correct! +10 points" << endl;
        score += 10;
    } else {
        cout << "Incorrect. The correct answer is a." << endl;
    }
    cout << "Your total score: " << score << endl;

    cout << "Question 3" << endl << "Which planet is too cold?" << endl;
    cout << "a. Pluto" << endl;
    cout << "b. Mars" << endl;
    cout << "c. Saturn" << endl;
    cout << "d. Unknown" << endl;

    cout << "Your answer (a/b/c/d): ";
    cin >> answer;

    if (answer == 'a') {
        cout << "Correct! +10 points" << endl;
        score += 10;
    } else {
        cout << "Incorrect. The correct answer is a." << endl;
    }

    cout << "Question 4" << endl << "Which planet is too hot?" << endl;
    cout << "a. Jupiter" << endl;
    cout << "b. Mars" << endl;
    cout << "c. Venus" << endl;
    cout << "d. Unknown" << endl;

    cout << "Your answer (a/b/c/d): ";
    cin >> answer;

    if (answer == 'c') 
    {
        cout << "Correct! +10 points" << endl;
        score += 10;
    } 
    else
    {
        cout << "Incorrect. The correct answer is c." << endl;
    }
    cout << "Your total score: " << score << endl;
    cout << "Question 5" << endl << "Which is the biggest planet?" << endl;
    cout << "a. Mars" << endl;
    cout << "b. Earth" << endl;
    cout << "c. Jupiter" << endl;
    cout << "d. Unknown" << endl;
    cout << "Your answer (a/b/c/d): ";
    cin >> answer;
    if (answer == 'c')
    {
        cout << "Correct! +10 points" << endl;
        score += 10;
    } 
    else 
    {
        cout << "Incorrect. The correct answer is c." << endl;
    }
    cout << "Your total score: " << score << endl;

    if (score >= 30)
    {
        cout << "You passed!" << endl;
    }
    else
    {
        cout << "You failed." << endl;
    }
    return 0;
}
