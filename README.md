## WeeklyChallengeOne


This project contains bugs and errors. You have to solely fix them up and find the best possible way to make the application run.

After you have successfully fixed it, you have to materialize it :smiley:. Use your creativity and showcase it in #showcase channel.

When you have fixed the errors just send a Pull Request to this GitHub repo.


## Where are the errors :

Errors are in `MainActivity.java` and `row_layout.xml`

After removing the bugs the application will look like this :


<img src = "https://i.imgur.com/DfIu4Aq.png" width=350>


## Solved Bugs Project

Some bugs are below :

1.  Inside row_layout there was ImageButton , it should be TextView

2. In MainActivity 
RecyclerView mRecyclerView; was not initialized .

3. set ContentView(R.layout.activity_main);
Should be Like below
setContentView(R.layout.activity_main);

4. RecyclerView.LayoutManager layoutManager = new LinearLayoutManager(thi);
it should be like below
RecyclerView.LayoutManager layoutManager = new LinearLayoutManager(this);