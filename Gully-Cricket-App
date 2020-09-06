#include <iostream>
#include<string>
#include<ctime>
#include<unistd.h>
using namespace std;

class Team{
public:
	void welcomeUsers();
	void displayPlayers();
	void display();
	int runs;
};
int playInning();
void selectBatsmanAndBowler1();
void selectBatsmanAndBowler2();
void decideWinner(int,int);
void Display2();
void Team::welcomeUsers(){
	cout<<"\n-------------------------------------------------\n"<<endl;
	cout<<"\tWelcome To Gully Cricket Game"<<endl;
	cout<<"\n-------------------------------------------------\n"<<endl;
	usleep(30000);
	 }
void Team:: displayPlayers() {
  string TeamA,TeamB;
  cout << "\nPress Enter to display players in Team: ";
  cin.get();
  cout << "Displaying players...\n";
  usleep(1000 * 1000);
  cout<<"-------------------------------------------------"<<endl;
  cout<<"*****************Team A:********************* \n1.M.S.Dhoni \n2.Virat kohli\n3.Manish Pandey\n"<<TeamA<<endl;

  cout<<"*******************Team B:******************* \n1.Navdeep saini \n2.Jasprit Bumrah \n3.Rohit Sharma"<<TeamB<<endl;
  cout<<"-------------------------------------------------"<<endl;

}
void Team::display(){
	cout<<"\n-------------------------------------------------\n"<<endl;
	cout<<"\t\tThank You"<<endl;
	cout<<"\n-------------------------------------------------\n"<<endl;
	usleep(30000);
}

int main() {
    Team t;
	t.welcomeUsers();
	t.displayPlayers();

	Team teamA,
	Display1();
	selectBatsmanAndBowler1();
    teamA.runs = playInning();

    Team teamB;
    Display2();
	selectBatsmanAndBowler2();
	teamB.runs=playInning();

	t.display();
	decideWinner(teamA.runs,teamB.runs);

	return 0;
}

void Display1() {
	cout << "\nPress Enter to start first inning ";
	cin.get();
	usleep(30000*10000);
	cout<<"First Inning started....\n";
}
void selectBatsmanAndBowler1() {
	cout<<"------Team A is batting team------\n";
    srand((unsigned) time(0));
    int result = 1 + (rand() % 3);
   switch (result) {
    case 1:
        printf("M.S.Dhoni");
        break;
    case 2:
        printf("Virat Kohli");
        break;
    case 3:
        printf("Manish Pandey");
        break;
    default:
        printf("Error");
        break;

}
   cout<<" is the batsman from batting team\n"<<endl;

   usleep(30000*10000);
   cout<<"------Team B is Bowling team------\n";
 srand((unsigned) time(0));
       int Result = 1 + (rand() % 3);
      switch (Result) {
       case 1:
           printf("Navdeep saini");
           break;
       case 2:
           printf("Jasprit Bumrah");
           break;
       case 3:
           printf("Rohit Sharma");
           break;
       default:
           printf("Error");
           break;

   }

      cout<<" is the bowler from bowling team\n"<<endl;
}
int playInning() {
	int runs,totalRuns=0;
    srand((unsigned) time(0));

    for (int i= 0; i< 5; i++) {
    runs = (rand() % 6) + 1;
    cout << "\nPress Enter.... ";
    cin.get();
    usleep(30000*10000);
    cout << "runs:" <<runs<< endl;
    totalRuns=totalRuns+runs;
}
     cout << "\nPress Enter to get final score.... ";
     cin.get();
     usleep(30000);
     cout<<"Final run scored by the team:"<<totalRuns<<endl;

     return runs;
}
void Display2() {
	cout << "\nPress Enter to start second inning ";
	cin.get();
	usleep(30000*10000);
	cout<<"second Inning started....\n";
}
void selectBatsmanAndBowler2() {

	cout<<"------Team B is batting team------\n";
    srand((unsigned) time(0));
    int result = 1 + (rand() % 3);
   switch (result) {
    case 1:
        printf("Navdeep saini");
        break;
    case 2:
        printf("Jasprit Bumrah");
        break;
    case 3:
        printf("Rohit Sharma");
        break;
    default:
        printf("Error");
        break;

}
   cout<<" is the Batsman from batting team\n"<<endl;
   usleep(30000);
   cout<<"------Team A is Bowling team------\n";
   srand((unsigned) time(0));
       int Result = 1 + (rand() % 3);
      switch (Result) {
       case 1:
           printf("M.S.Dhoni");
           break;
       case 2:
           printf("Virat Kohli");
           break;
       case 3:
           printf("Manish Pandey");
           break;
       default:
           printf("Error");
           break;

   }
      cout<<" is the bowler from bowling team\n"<<endl;
}
void decideWinner(int teamAScore, int teamBScore) {

	if (teamAScore > teamBScore) {
        cout << "\t\t !!Team A is the Winner!!" << endl;
    } else if (teamAScore < teamBScore) {
        cout<< "\t\t !!Team B is the Winner!!" << endl;
    } else {
        cout << "\t\t Match Draw" << endl;


}
}

/*OUTPUT:
-------------------------------------------------

	Welcome To Gully Cricket Game

-------------------------------------------------


Press Enter to display players in Team: 
Displaying players...
-------------------------------------------------
*****************Team A:********************* 
1.M.S.Dhoni 
2.Virat kohli
3.Manish Pandey

*******************Team B:******************* 
1.Navdeep saini 
2.Jasprit Bumrah 
3.Rohit Sharma
-------------------------------------------------
------Team A is batting team------
Manish Pandey is the batsman from batting team

------Team B is Bowling team------
Rohit Sharma is the bowler from bowling team


Press Enter.... 
runs:3

Press Enter.... 
runs:1

Press Enter.... 
runs:3

Press Enter.... 
runs:6

Press Enter.... 
runs:4

Press Enter to get final score.... 
Final run scored by the team:17

Press Enter to start second inning 
second Inning started....
------Team B is batting team------
Rohit Sharma is the Batsman from batting team

------Team A is Bowling team------
Manish Pandey is the bowler from bowling team


Press Enter.... 
runs:3

Press Enter.... 
runs:5

Press Enter.... 
runs:5

Press Enter.... 
runs:4

Press Enter.... 
runs:5

Press Enter to get final score.... 
Final run scored by the team:22

-------------------------------------------------

		Thank You

-------------------------------------------------

		 !!Team B is the Winner!!
		 
*/		 
		 
