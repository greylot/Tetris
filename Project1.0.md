#1 static list <list<int>> pieces = [
 2   [ 4 , 5 , 14 , 15 ],     // piece 0
 3   [ 4 , 14 , 24 , 25 ],    // piece 1
 4   [ 5 , 15 , 24 , 25 ],    // piece 2
 5   [ 4 , 14 , 24 , 34 ],    // piece 3
 6   [ 4 , 14 , 15 , 25 ],    // piece 4
 7   [ 5 , 15 , 14 , 24 ],    // piece 5
 8   [ 4 , 5 , 6 , 15 ],      // piece 6
 9 ];
10      GestureDetector(
11        onTap: startgame,
12      child: Mybutton(
13       child:Text(
14          "PLAY",
15        ),
16      ),
17    )
18
