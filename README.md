<main class="col-md markdown-body">

<h1 id="notes">Notes</h1>

<h2 id="distribution-code">Distribution Code</h2>

<p>Download this project’s <a href="https://cdn.cs50.net/2019/fall/tracks/android/notes/notes.zip">distribution code</a>.</p>

<p>To open the distribution code, extract the ZIP, open Android Studio, select “Import project”, and select the folder you extracted from the ZIP.</p>

<h2 id="what-to-do">What To Do</h2>

<ul>
  <li data-marker="*">Deleting Notes</li>
</ul>

<h2 id="deleting-notes">Deleting Notes</h2>

<p>So far, our Notes app can add and edit notes. Let’s add the ability for a user to delete a note when they no longer need it.</p>

<p>First, add a new method called <code class="highlighter-rouge">delete</code> to the <code class="highlighter-rouge">NoteDao</code> interface. You’ll probably want this method to take an <code class="highlighter-rouge">id</code> of the note to delete, and use a <code class="highlighter-rouge">DELETE</code> query.</p>

<p>Next, add a button to your layout for deleting notes. Exactly what the UI looks like is up to you! (If you’re feeling ambitious, you can try implementing a UI that allows a user to swipe on a note from the list to delete it, much like many email apps on Android.)</p>

<p>Finally, wire up that UI to a method that calls your new <code class="highlighter-rouge">delete</code> method on the <code class="highlighter-rouge">NoteDao</code>. Depending on your UI, you might find the <code class="highlighter-rouge">finish</code> method helpful—this method will dismiss the current activity and go back to the previous one.</p>

<p>To test your app, try creating a few notes and then deleting them, to make sure the right things get deleted!</p>

<h2 id="how-to-submit">How to Submit</h2>

<p>To submit your code with <code class="highlighter-rouge">submit50</code>, you may either: (1) upload your code to CS50 IDE and run <code class="highlighter-rouge">submit50</code> from inside of your IDE, or (2) install <code class="highlighter-rouge">submit50</code> on your own computer by running <code class="highlighter-rouge">pip3 install submit50</code> (assuming you have <a href="https://www.python.org/downloads/">Python 3</a> installed).</p>

<p>Execute the below, logging in with your GitHub username and password when prompted. For security, you’ll see asterisks (<code class="highlighter-rouge">*</code>) instead of the actual characters in your password.</p>

<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><code>submit50 cs50/problems/2020/x/tracks/android/notes
</code></pre></div></div>


</main>
