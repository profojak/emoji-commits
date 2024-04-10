<!-- Emoji Commits ------------------------------------------------------------>

<div align="center">
  <h2>⭐💥🪲📄<br>Emoji Commits</h1>

  A guide to writing great commit messages with emojis!

  <code>&emsp;   ♻️ npc: Move unicorns class away from donkeys folder   &emsp;</code><br>
  <code>&emsp;   🧪 ai: Check if multiple chickens safely cross road    &emsp;</code><br>
  <code>&emsp;   🎨 sprite: Change color of rubber ducks to yellowish   &emsp;</code><br>
  <code>&emsp;   🪲 buff: Forbid squirrels from obtaining speed buff    &emsp;</code><br>

  <sup>
    Built with ❤️ by <a href="https://github.com/profojak">Jakub Profota</a>
  </sup>
  <br><br>

  <table><tr><td>
    <b>
      <a href="#emoji">&lt;emoji&gt;</a>&nbsp;
      <a href="#scope">&lt;optional scope&gt;</a>:&nbsp;
      <a href="#summary">&lt;summary&gt;</a>
    </b>&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &ensp;
    <br>blank line<br>
    <b><a href="#body">&lt;optional body&gt;</a></b>
    <br>blank line<br>
    <b><a href="#footer">&lt;optional footer&gt;</a></b>
  </td></tr></table>
</div>

<!-- Emoji -------------------------------------------------------------------->

<h3>Emoji</h3>
Select a commit type from the table below based on the action you intend to take.
Start your commit message with the corresponding emoji. Use the symbol
<code>🎉</code> instead of the shortcode <code>:tada:</code>. To help you choose,
try to finish the sentence:
<br><br>

<div align="center">
  <i>This commit should...</i><br><br>
  <table>
    <tr>
      <td><a href="https://emojipedia.org/star">Star</a></td><td>⭐</td>
      <td align="right"><b>Add</b></td>
      <td align="left" rowspan=2><i>...a new feature<br>to the project.</i></td>
    </tr>
    <tr><td colspan=3><code>U+2B50</code> <code>:star:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/collision">Collision</a></td><td>💥</td>
      <td align="right"><b>Remove</b></td>
      <td align="left" rowspan=2><i>...an existing feature<br>from the project.</i></td>
    </tr>
    <tr><td colspan=3><code>U+1F4A5</code> <code>:collision:</code> <code>:boom:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/beetle">Beetle</a></td><td>🪲</td>
      <td align="right"><b>Fix</b></td>
      <td align="left" rowspan=2><i>...a bug, error, etc.<br>&nbsp;</i></td>
    </tr>
    <tr><td colspan=3><code>U+1FAB2</code> <code>:beetle:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/page-facing-up">Page<br>Facing Up</a></td><td>📄</td>
      <td align="right"><b>Document</b></td>
      <td align="left" rowspan=2><i>...the project with docs,<br>comments, readmes, etc.<br>&nbsp;</i></td>
    </tr>
    <tr><td colspan=3><code>U+1F4C4</code> <code>:page_facing_up:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/artist-palette">Artist<br>Palette</a></td><td>🎨</td>
      <td align="right"><b>Style</b></td>
      <td align="left" rowspan=2><i>...the code formatting,<br>change colors, etc.<br>&nbsp;</i></td>
    </tr>
    <tr><td colspan=3><code>U+1F3A8</code> <code>:art:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/recycling-symbol">Recycling<br>Symbol</a></td><td>♻️</td>
      <td align="right"><b>Refactor</b></td>
      <td align="left" rowspan=2><i>...a file structure,<br>code structure, etc.<br>&nbsp;</i></td>
    </tr>
    <tr><td colspan=3><code>U+267B</code> <code>:recycle:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/rocket">Rocket</a></td><td>🚀</td>
      <td align="right"><b>Optimize</b></td>
      <td align="left" rowspan=2><i>...performance,<br>memory, etc.</i></td>
    </tr>
    <tr><td colspan=3><code>U+1F680</code> <code>:rocket:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/test-tube">Test<br>Tube</a></td><td>🧪</td>
      <td align="right"><b>Test</b></td>
      <td align="left" rowspan=2><i>...the project with unit<br>tests, integration, etc.<br>&nbsp;</i></td>
    </tr>
    <tr><td colspan=3><code>U+1F9EA</code> <code>:test_tube:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/gear">Gear</a></td><td>⚙️</td>
      <td align="right"><b>Configure</b></td>
      <td align="left" rowspan=2><i>...the environment,<br> build system, CI/CD, etc.</i></td>
    </tr>
    <tr><td colspan=3><code>U+2699</code> <code>:gear:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/bucket">Bucket</a></td><td>🪣</td>
      <td align="right"><b>Maintain</b></td>
      <td align="left" rowspan=2><i>...the project<br>with various chores.</i></td>
    </tr>
    <tr><td colspan=3><code>U+1FAA3</code> <code>:bucket:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/party-popper">Party<br>Popper</a></td><td>🎉</td>
      <td align="right"><b>Celebrate</b></td>
      <td align="left" rowspan=2><i>...the initial commit,<br> a milestone, etc.<br>&nbsp;</i></td>
    </tr>
    <tr><td colspan=3><code>U+1F389</code> <code>:tada:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/handshake">Handshake</a></td><td>🤝</td>
      <td align="right"><b>Merge</b></td>
      <td align="left" rowspan=2><i>...branches.<br>&nbsp;</i></td>
    </tr>
    <tr><td colspan=3><code>U+1F91D</code> <code>:handshake:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/scissors">Scissors</a></td><td>✂️</td>
      <td align="right"><b>Revert</b></td>
      <td align="left" rowspan=2><i>...changes.<br>&nbsp;</i></td>
    </tr>
    <tr><td colspan=3><code>U+2702</code> <code>:scissors:</code></td></tr>
    <tr>
      <td><a href="https://emojipedia.org/construction">Construction</a></td><td>🚧</td>
      <td align="right"><b>Continue</b></td>
      <td align="left" rowspan=2><i>...an unfinished work<br>in progress.</i></td>
    </tr>
    <tr><td colspan=3><code>U+1F6A7</code> <code>:construction:</code></td></tr>
  </table>
</div>

<!-- Scope -------------------------------------------------------------------->

<h3>Scope</h3>
Optionally, provide a scope with additional contextual information, unless the
commit change is global or difficult to assign. The scope refers to a section of
the project. Put a single space <code> </code> before the scope and a colon
<code>:</code> right after it:
<br><br>

<div align="center">
  ✅ <code>🚀 math: Decrease time complexity of addition</code>
  &emsp; &emsp; &emsp; &emsp; &nbsp;<br>&emsp; &emsp; &emsp; &emsp; &emsp;
  <code>🚀 math Decrease time complexity of addition</code> ❌
  <br>&emsp; &emsp; &emsp; &emsp; &emsp;
  <code>🚀math: Decrease time complexity of addition</code> ❌
</div>

<!-- Summary ------------------------------------------------------------------>

<h3>Summary</h3>
Write a summary of the commit. Start with an imperative present active verb, as
if you were giving an order. Ommit <code>a</code>, <code>an</code> and
<code>the</code> articles to save characters. Capitalize the first letter and end
without a sentence-ending period. Insert a single space <code> </code> before the
summary:
<br><br>

<div align="center">
  ✅ <code>🎨 sprite: Add more bones to skeletons</code>
  &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;
  <br>&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &ensp;
  <code>🎨 sprite: More bones to skeletons</code> ❌
  <br>&emsp; &emsp; &emsp; &emsp; &emsp; &ensp; &ensp; &nbsp; &nbsp; &nbsp;
  <code>🎨 sprite:Add more bones to skeletons</code> ❌
  <br>&emsp; &emsp; &emsp; &emsp; &emsp; &ensp; &nbsp; &nbsp; &nbsp;&nbsp;
  <code>🎨 sprite: add more bones to skeletons</code> ❌
  <br>&emsp; &emsp; &emsp; &emsp; &emsp; &ensp; &emsp;&nbsp;
  <code>🎨 sprite: Add more bones to skeletons.</code> ❌
  <br>&emsp; &emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&nbsp;
  <code>🎨 sprite: Adds more bones to skeletons</code> ❌
  <br>&emsp; &emsp; &emsp; &emsp; &emsp; &ensp;&ensp;&nbsp;&nbsp;
  <code>🎨 sprite: Added more bones to skeletons</code> ❌
  <br>&emsp; &emsp; &emsp; &emsp; &emsp;&emsp;&nbsp;
  <code>🎨 sprite: Adding more bones to skeletons</code> ❌
</div>

<!-- Body --------------------------------------------------------------------->

<h3>Body</h3>
Optionally, continue with a longer message body. Describe the why and how. Include
any motivation, such as a goal, use case, user story, etc. Mention any relevant
algorithms, protocols, etc. Prefer imperative, present active verbs. Prefer fully
qualified URLs to link to issues, commits, etc. Hard wrap the text after reaching
a characters-per-line limit that makes sense to you. Do not wrap atypical text such
as URLs, terminal output, code snippets, etc. Insert a blank line before each body
paragraph:
<br><br>

<div align="center">
<pre>✅ 🪲 sound: Stop playing scary roars at street market      &emsp;<br>
Why...                                               &emsp;<br>
How...                                               &emsp;<br>
See: https://github.com/profojak/repo/issues/42      &emsp;</pre>
<pre>&emsp;   🪲 sound: Stop playing scary roars at street market     ❌
How...                                               &emsp;
Why...                                               &emsp;
Resolves issue #42                                   &emsp;</pre>
</div>

<!-- Footer ------------------------------------------------------------------->

<h3>Footer</h3>
Optionally, end with a trailer footer. List each Git trailer on a separate line.
Insert a blank line before the footer, but not between individual trailers.
Separate keys from values with a colon <code>:</code> and a single space
<code> </code>:
<br><br>

<div align="center">
  ✅ <code>Co-authored-by: Foo Bar &lt;foo@bar.git&gt;</code>
  &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;&ensp;
  <br>&emsp; &emsp; &emsp; &emsp; &emsp; &ensp; &ensp; &ensp; &nbsp; &nbsp;&nbsp;
  <code>Co-authored-by Foo Bar &lt;foo@bar.git&gt;</code> ❌
  <br>&emsp; &emsp; &emsp; &emsp; &emsp; &emsp;&emsp;
  <code>Co-authored-by:   Foo Bar &lt;foo@bar.git&gt;</code> ❌
  <br>
</div>
<h1></h1>

<!-- Acknowledgments ---------------------------------------------------------->

<h3>Acknowledgments</h3>
Many thanks to the open source community and the countless developers who have
shared their knowledge and best practices in commit messaging. Your efforts have
greatly enriched this guide! Special thanks to:
<br><br>
<div align="center">
  • Authors of
    <a href="https://www.conventionalcommits.org/en/v1.0.0/">Conventional Commits</a>
  &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;&ensp;<br>
  • <a href="https://github.com/joelparkerhenderson">Joel Parker Henderson</a>'s
    <a href="https://github.com/joelparkerhenderson/git-commit-message">
      Git commit message</a>
  &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &ensp;<br>
  • <a href="https://github.com/ahmadawais">Ahmad Awais</a>'s
    <a href="https://github.com/ahmadawais/Emoji-Log">Emoji Log</a>
  &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;
  &ensp; &nbsp;&nbsp;<br>
  • Tim Pope's
    <a href="https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html">
      note on Git commit messages</a>
  &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &ensp;&nbsp;
</div>

<!----------------------------------------------------------------------------->
