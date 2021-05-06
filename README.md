# maarkdown-test
The main idea of this repo is to test how html tags within markdown will appear in github:

The following variables will be used in this test:

<pre class="prettyprint lang-sh">
<var>DBNAME</var> = for example: MYDB
<var>GCS_BUCKET</var> = path to a GCS bucket
</pre>

<pre class="prettyprint lang-sh">
<var>DBNAME</var>/deploy/install.sh
</pre>

**Perform the steps:**

*   Do one thing
*   Do another thing

<pre class="prettyprint lang-sh">
    $ gsutil mb gs://<var>GCS_BUCKET</var>

    $ gsutil cp ~/Downloads/file1.zip gs://<var>GCS_BUCKET</var>/install/
    $ gsutil cp ~/Downloads/file-2.zip  gs://<var>GCS_BUCKET</var>/install/
    $ gsutil cp ~/Downloads/file-3.zip  gs://<var>GCS_BUCKET</var>/install/
 </pre>
