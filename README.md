SQLiteUnityKit
==============

Framework to connect to SQLite database from Unity for iOS, MAC and Windows

<b>***** please don't use this code for sell an asset *****</b>


 * First version developed by Poya  @  http://gamesforsoul.com/

 * BLOB support by Jonathan Derrough @ http://jderrough.blogspot.com/

 * modify by Santiago Bustamante @ busta117@gmail.com
<br/>
<br/>

<b>HOW TO USE:</b><br/>

<code>
SqliteDatabase sqlDB = new SqliteDatabase(“config.db”);<br/>
string query = “INSERT INTO User(UserName) VALUES( ‘Santiago’)”;<br/>
sqlDB.ExecuteNonQuery(query);<br/>
</code>
<br/>

<b>to execute a query this libs have 2 simple methods:<br/></b>
<code> void ExecuteNonQuery(string query) </code> for SQL query like UPDATE, DELETE....<br/>
<code> Dictionary ExecuteQuery(string query) </code> for SQL query like SELECT ....<br/>