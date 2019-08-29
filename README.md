# laravel-multi-auth

<article><p>##Windows users:</p>
<ul>
<li>Download xampp: <a href="https://www.apachefriends.org/download.html" target="_blank">https://www.apachefriends.org/download.html</a></li>
<li>Download and extract cmder mini: <a href="https://github.com/hardeepbharaj1295/laravel-multi-auth/archive/master.zip" target="_blank">https://github.com/hardeepbharaj1295/laravel-multi-auth/archive/master.zip</a></li>
</ul>
<p>##Mac Os, Ubuntu and windows users continue here:</p>
<ul>
<li>Create a database locally named <code>laravel_multi_auth</code> utf8_general_ci</li>
<li>Download composer <a href="https://getcomposer.org/download/" target="_blank" rel="nofollow">https://getcomposer.org/download/</a></li>
<li>Pull Laravel/php project from git provider.</li>
<li>Rename <code>.env.example</code> file to <code>.env</code>inside your project root and fill the database information.
(windows wont let you do it, so you have to open your console cd your project root directory and run <code>mv .env.example .env</code> )</li>
<li>Open the console and cd your project root directory</li>
<li>Run <code>composer install</code> or <code>php composer.phar install</code></li>
<li>Run <code>php artisan migrate</code></li>
<li>Run <code>php artisan db:seed</code> to run seeders, if any.</li>
<li>Run <code>php artisan serve</code></li>
    <li>Run <code>php artisan key:generate</code></li>    
</ul>

<p>#####You can now access your project at localhost:8000 :)</p>
<h2><a id="user-content-if-for-some-reason-your-project-stop-working-do-these" class="anchor" aria-hidden="true" href="#if-for-some-reason-your-project-stop-working-do-these"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>If for some reason your project stop working do these:</h2>
<ul>
<li><code>composer install</code></li>
<li><code>php artisan migrate</code></li>
</ul>
<h2>It should typically be available on http://localhost:8000</h2>
<hr>
<p>Remember to visit <code>http://localhost:8000/register/writer</code> and <code>http://localhost:8000/register/admin</code> to register writers and admins respectively. Then visit  <code>http://localhost:8000/login/writer</code> and <code>http://localhost:8000/login/admin</code> to login the writers and admins respectively.</p>
</article>
