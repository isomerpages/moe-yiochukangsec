---
title: HTML Kitchen Sink
permalink: /htmlkitchensink/
description: This page will show what various HTML elements will look like using
  the default stylesheets (aka and in strict order ... styles.css,
  blueprint.css, custom.css)
variant: markdown
image: /images/0cd1870b_103f_4767_8dfd_9abfe6e11817.jpg
---
<h2>Responsive Columns using CSS Multi-column Layout</h2>
   <div class="container">
        <div class="card">
            <h3>Band</h3>
             <img src="/images/Our%20Curriculum/Non%20Academic%20Programmes/CoCurricular%20Activities/Performing%20Arts/Band.jpg">
        </div>
        <div class="card">
            <h3>Drama</h3>
           <img src="/images/Our%20Curriculum/Non%20Academic%20Programmes/CoCurricular%20Activities/Performing%20Arts/EngDrama.jpg">
        </div>
        <div class="card">
            <h3>Choir</h3>
             <img src="/images/Our%20Curriculum/Non%20Academic%20Programmes/CoCurricular%20Activities/Performing%20Arts/Choir.jpg">
        </div>
    </div>
		
<style>
        
        
        h2 {
            margin-bottom: 15px;
            color: #2c3e50;
        }
        
        p {
            line-height: 1.6;
        }
  </style>


<hr>

<details>
	<summary>About the HTML Kitchen Sink</summary>
	<header role="banner">
  <h1>HTML5 Kitchen Sink</h1>
  <small>Jump to: <a href="#headings">Headings</a> |
    <a href="#sections">Sections</a> |
    <a href="#phrasing">Phrasing</a> |
    <a href="#palpable">Palpable Content</a> |
    <a href="#embeds">Embeds</a> | <a href="#forms">Forms</a> |
    <a href="#tables">Tables</a>
  </small>
  <br><br>
  <p>This section serves as the <code>header</code>.</p>
</header>
<hr>
<main>
  <section id="headings">
    <h3><a href="#headings">#</a> Headings</h3>
    <p>
      Elements <code>h1</code>, <code>h2</code>, <code>h3</code>,
      <code>h4</code>, <code>h5</code>, <code>h6</code> make up
      the <em>heading content</em> category.
    </p>
    <hgroup>
      <h1>h1 I am most important.</h1>
      <h2>h2 Back in my quaint <a href="#">garden</a></h2>
      <h3>
        h3 Jaunty <a href="#">zinnias</a> vie with flaunting
        phlox.
      </h3>
      <h4>
        h4 Five or six big jet planes zoomed quickly by the new
        tower.
      </h4>
      <h5>
        h5 Expect skilled signwriters to use many jazzy, quaint
        old alphabets effectively.
      </h5>
      <h6>h6 Pack my box with five dozen liquor jugs.</h6>
    </hgroup>
    <footer>
      <p>
        See the
        <a href="https://www.w3.org/TR/html5/dom.html#heading-content" target="_blank">Heading Content spec.</a>
      </p>
      <p>
        Note: these two paragraphs are contained in a
        <code>footer</code> element.
      </p>
    </footer>
  </section>
  <hr>
  <section id="sections">
    <header>
      <h3><a href="#sections">#</a> Sections</h3>
      <p>
        Elements <code>article</code>, <code>aside</code>,
        <code>nav</code>, <code>section</code> make up the
        <em>sectioning content</em> category.
      </p>
      <nav>
        <p>
          These links are contained in a
          <code>nav</code> element.
        </p>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>
    <article>
      <p>
        This paragraph is nested inside an
        <code>article</code> element. It contains many
        different, sometimes useful,
        <a href="http://www.w3schools.com/tags/">HTML5 elements</a>. Of course there are classics like <em>emphasis</em>,
        <strong>strong</strong>, and <small>small</small> but
        there are many others as well. Hover the following text
        for abbreviation element:
        <abbr title="abbreviation">abbr</abbr>. You can define
        <del>deleted text</del> which often gets replaced with
        <ins>inserted</ins> text.
      </p>
      <p>
        You can also use <kbd>keyboard text</kbd>, which
        sometimes is styled similarly to the
        <code>&lt;code&gt;</code> or <samp>samp</samp> elements.
        Even more specifically, there is an element just for
        <var>variables</var>. Not to be mistaken with block
        quotes below, the quote element lets you denote
        something as <q>quoted text</q>. Lastly don't forget the
        sub (H<sub>2</sub>O) and sup (E = MC<sup>2</sup>)
        elements.
      </p>
      <section>
        <p>
          This paragraph is contained in a
          <code>section</code> element of its parent
          <code>article</code> element.
        </p>
        <p>
          ↓ The following paragraph has the
          <code>hidden</code> attribute and should not be
          displayed. ↓
        </p>
        <p hidden="">→ You should not see this paragraph. ←</p>
        <p>
          ↑ The previous paragraph should not be displayed. ↑
        </p>
      </section>
    </article>
    <aside>
      <p>This is contained in an <code>aside</code> element.</p>
    </aside>
    <footer>
      <p>
        See the
        <a href="https://www.w3.org/TR/html5/dom.html#sectioning-content" target="_blank">Sectioning Content spec.</a>
      </p>
    </footer>
  </section>
  <hr>
  <section id="phrasing">
    <header>
      <h3><a href="#phrasing">#</a> Phrasing</h3>
      <p>
        Elements <code>abbr</code>, <code>b</code>,
        <code>bdi</code>, <code>bdo</code>, <code>br</code>,
        <code>cite</code>, <code>code</code>, <code>data</code>,
        <code>del</code>, <code>dfn</code>, <code>em</code>,
        <code>i</code>, <code>ins</code>, <code>kbd</code>,
        <code>mark</code>, <code>meter</code>,
        <code>progress</code>, <code>q</code>, <code>s</code>,
        <code>samp</code>, <code>small</code>,
        <code>span</code>, <code>strong</code>,
        <code>sub</code>, <code>sup</code>, <code>time</code>,
        <code>u</code>, <code>var</code>, <code>wbr</code>, and
        others make up the <em>phrasing content</em> category.
      </p>
    </header>
    <p>
      <code>abbr</code>: Some vehicles meet the
      <abbr title="Super Ultra Low Emission Vehicle">SULEV</abbr>
      standard.<br>
      <code>br</code> was used to make this sentence start on a
      new line.
    </p>
    <p>
      <code>bdi</code>: Some languages read right to left,
      <bdi lang="ar">مرحبا</bdi>. <code>bdo</code>:
      <bdo dir="rtl">The normal direction has been overridden.</bdo>
    </p>
    <p>
      <code>em</code> is used for <em>emphasis</em> and usually
      renders as italics, contrast that with <code>i</code> which
      is used for alternate voice or to offset from the normal
      (such as a phrase from a different language or taxonomic
      designation): <i>E. coli</i> can be bad.
      <code>strong</code> is used for
      <strong>importance or urgency</strong> and usually renders
      as bold, contrast that with <code>b</code> which is used to
      <b>draw attention</b> without the semantic meaning of
      importance.
    </p>
    <p>
      <code>cite</code>: In the words of
      <cite>Charles Bukowski</cite> —
      <q>An intellectual says a simple thing in a hard way. An
        artist says a hard thing in a simple way.</q>
    </p>
    <p>
      <code>data</code> can be used to specify
      <data value="2018-09-24T05:00-07:00">5 A.M.</data> that is
      machine-readable, but <code>time</code> is a better choice
      for specifying
      <time datetime="2018-09-24T05:00-07:00">5 A.M.</time> in a
      machine-readable format.
    </p>
    <p>
      <code>del</code> can be
      <del datetime="2017-10-11T01:25-07:00">varily</del> used to
      mark deletions. <code>ins</code> marks
      <ins datetime="2007-12-19 00:00Z">insertions</ins>.
      <code>s</code>: similar to <code>del</code>, but used to
      mark content that is no longer relevant.
      <s>Windows XP version available.</s> <code>u</code>: a
      holdover with no real meaning that should be <u>removed</u>.
      <code>mark</code>: the HTML equivalent of the
      <mark>yellow highlighter</mark>. <code>span</code>: a
      <span>generic element</span> with no meaning by itself.
    </p>
    <p>
      <code>dfn</code>: Foreign phrases add a certain
      <dfn title="French: indefinable quality" lang="fr">je ne sais quoi</dfn>
      to one's prose.
    </p>
    <p>
      <code>q</code>: The W3C page <cite>About W3C</cite> says the
      W3C’s mission is
      <q cite="https://www.w3.org/Consortium/">To lead the World Wide Web to its full potential by
        developing protocols and guidelines that ensure
        long-term growth for the Web</q>.
    </p>
    <p><code>kbd</code> and <code>samp</code>: I did this:</p>
    <pre><samp>c:\&gt;<kbd>format c: /yes</kbd></samp></pre>
    <p>
      Is that bad? Press <kbd><kbd>Ctrl</kbd></kbd>+<kbd><kbd>F5</kbd></kbd> for a hard reload.
    </p>
    <p>
      <code>var</code>: To log in, type
      <kbd>ssh <var>user</var>@example.com</kbd>, where
      <var>user</var> is your user ID.
    </p>
    <p>
      <code>meter</code> and <code>progress</code>: Storage space
      usage:
      <meter max="8" value="6">
        6 blocks used (out of 8 total)
      </meter>
      Progress:
      <progress max="100" value="37">37%</progress>
    </p>
    <p>
      <code>sub</code> is used for subscripts: H<sub>2</sub>O.
      <code>sup</code> is used for superscripts: E =
      MC<sup>2</sup>. <code>small</code> is used for side
      comments:
      <q>I wrote this whole document.
        <small>[Editor's note: no he did not]</small></q>
      <code>wbr</code>: used to specify where a word may break and
      it is super<wbr>cali<wbr>fragil<wbr>istic<wbr>expiali<wbr>do<wbr>cious.
    </p>
    <footer>
      <p>
        See the
        <a href="https://www.w3.org/TR/html5/dom.html#phrasing-content" target="_blank">Phrasing Content spec.</a>
      </p>
    </footer>
  </section>
  <hr>
  <section id="palpable">
    <header>
      <h3><a href="#palpable">#</a> Palpable Content</h3>
      <p>
        Elements <code>a</code>, <code>address</code>,
        <code>blockquote</code>, <code>button</code>,
        <code>details</code>, <code>dl</code>,
        <code>fieldset</code>, <code>figure</code>,
        <code>form</code>, <code>input</code>,
        <code>label</code>, <code>map</code>, <code>ol</code>,
        <code>output</code>, <code>pre</code>,
        <code>select</code>, <code>table</code>,
        <code>textarea</code>, <code>ul</code>, and others make
        up the <em>palpable content</em> category.
      </p>
    </header>
    <p><code>a</code>: <a href="http://example.com">Example</a>.</p>
    <p><code>address</code>:</p>
    <address>
      1 Infinite Loop<br>
      Cupertino, CA 95014<br>
      United States
    </address>
    <p><code>blockquote</code>:</p>
    <blockquote>
      <p>
        I quickly explained that many big jobs involve few
        hazards
      </p>
    </blockquote>
    <blockquote>
      <p>
        This is a mult-line blockquote with a cite reference.
        People think focus means saying yes to the thing you’ve
        got to focus on. But that’s not what it means at all. It
        means saying no to the hundred other good ideas that
        there are. You have to pick carefully. I’m actually as
        proud of the things we haven’tdone as the things I have
        done. Innovation is saying no to 1,000 things.
      </p>
      <footer>
        Steve Jobs,
        <cite>Apple Worldwide Developers’ Conference, 1997</cite>
      </footer>
    </blockquote>
    <p><code>details</code> and <code>summary</code>:</p>
    <details>
      <summary>
        Copying...
        <progress value="97543282" max="375505392"></progress>
        25%
      </summary>
      <dl>
        <dt>Transfer rate:</dt>
        <dd>452KB/s</dd>
        <dt>Duration:</dt>
        <dd>01:16:27</dd>
        <dt>Color profile:</dt>
        <dd>SD (6-1-6)</dd>
        <dt>Dimensions:</dt>
        <dd>320×240</dd>
      </dl>
    </details>
    <p><code>dl</code>:</p>
    <dl>
      <dt>Definition List Title</dt>
      <dd>Definition list division.</dd>
      <dt>Kitchen Sink</dt>
      <dd>
        Used in expressions to describe work in which all
        conceivable (and some inconceivable) sources have been
        mined. In this case, a bunch of markup.
      </dd>
      <dt>aside</dt>
      <dd>Defines content aside from the page content</dd>
      <dt>blockquote</dt>
      <dd>
        Defines a section that is quoted from another source
      </dd>
    </dl>
    <p><code>figure</code>:</p>
    <figure>
      <img src="https://www.yiochukangsec.moe.edu.sg/images/Our%20Curriculum/Non%20Academic%20Programmes/CoCurricular%20Activities/Uniformed%20Groups/Red%20Cross%20Youth/R1.jpg">
      <figcaption>
        Figure 1: A picture the Red Cross Youth
        <a href="https://www.yiochukangsec.moe.edu.sg/cca/Uniformed-Groups/Red-Cross-Youth/"></a>
      </figcaption>
    </figure>
    <br><br>
    <h4><a href="#forms">#</a> Forms</h4>
    <hr>
    <form>
			<p>Seems like they really don't want the form fields to be displayed prominently ...</p>
      <p>
        <label for="example-input-email">Email address</label>
        <input id="example-input-email" type="email">
      </p>
      <p>
        <label for="example-input-number">Number</label>
        <input id="example-input-number" type="number">
      </p>
      <p>
        <label for="example-input-password">Password</label>
        <input id="example-input-password" type="password">
      </p>
      <p>
        <label for="example-input-search">Search</label>
        <input id="example-input-search" type="search">
      </p>
      <p>
        <label for="example-input-tel">Telephone number</label>
        <input id="example-input-tel" type="tel">
      </p>
      <p>
        <label for="example-input-text">Text</label>
        <input id="example-input-text" type="text">
      </p>
      <p>
        <label for="example-input-readonly">Read-only</label>
        <input value="Can't touch this!" readonly="" type="text">
      </p>
      <p>
        <label for="example-input-disabled">Disabled</label>
        <input value="Not available" disabled="" type="text">
      </p>
      <p>
        <label for="example-input-url">URL</label>
        <input id="example-input-url" type="url">
      </p>
      <p>
        <label for="example-input-color">Color</label>
        <input id="example-input-color" type="color">
      </p>
      <p>
        <label for="example-input-date">Date</label>
        <input id="example-input-date" type="date">
      </p>
      <p>
        <label for="example-input-date-time">Date / Time</label>
        <input id="example-input-date-time" type="datetime">
      </p>
      <p>
        <label for="example-input-date-time-local">Date / Time local</label>
        <input id="example-input-date-time-local" type="datetime-local">
      </p>
      <p>
        <label for="example-input-month">Month</label>
        <input id="example-input-month" type="month">
      </p>
      <p>
        <label for="example-input-week">Week</label>
        <input id="example-input-week" type="week">
      </p>
      <p>
        <label for="example-input-time">Time</label>
        <input id="example-input-time" type="time">
      </p>
      <p>
        <label for="example-input-file">File input</label>
        <input id="example-input-file" type="file">
      </p>
      <p>
        <label for="example-input-range">Range input</label>
        <input value="3" max="4" min="1" id="example-input-range" type="range">
      </p>
      <p>
        <label for="example-select1">Select</label>
        <select id="example-select1">
          <option>1</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
        </select>
      </p>
      <p>
        <label for="example-select1a">Select with size</label>
        <select size="2" id="example-select1a">
          <option>1</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
        </select>
      </p>
      <p>
        <label for="example-select2">Multiple select</label>
        <select id="example-select2" multiple="">
          <option>1</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
        </select>
      </p>
      <p>
        <label for="example-optgroup">Select with optgroup: Favorite Car</label>
        <select id="example-optgroup">
          <optgroup label="Swedish Cars">
            <option>Volvo</option>
            <option>Saab</option>
          </optgroup>
          <optgroup label="German Cars">
            <option>Mercedes</option>
            <option>Audi</option>
          </optgroup>
        </select>
      </p>
      <p>
        <label for="example-optgroup2">Select with optgroup and size: Favorite Dish</label>
        <select size="2" id="example-optgroup2">
          <optgroup label="Vegetarian">
            <option>Green Salad</option>
            <option>French Fries</option>
          </optgroup>
          <optgroup label="Carnivorous">
            <option>Big Mac</option>
            <option>Roast Beef</option>
          </optgroup>
        </select>
      </p>
      <p>
        <label for="example-optgroup3">Multiple select with optgroup: Public
          transport</label>
        <select multiple="" id="example-optgroup3">
          <optgroup label="Ground">
            <option>Train</option>
            <option>Bus</option>
          </optgroup>
          <optgroup label="Water">
            <option>Ship</option>
            <option>Submarine</option>
          </optgroup>
          <optgroup label="Air">
            <option>Plane</option>
            <option>Balloon</option>
          </optgroup>
        </select>
      </p>
      <p>
        <label for="example-textarea">Textarea</label>
        <textarea rows="3" id="example-textarea"></textarea>
      </p>
      <fieldset>
        <legend>I am legend</legend>
        <div>
          <input checked="" value="option1" id="option-radio1" name="option-radio" type="radio">
          <label for="option-radio1">Option one is this and that—be sure to
            include why it's great</label>
        </div>
        <div>
          <input value="option2" id="option-radio2" name="option-radio" type="radio">
          <label>Option two can be something else and selecting
            it will deselect option one</label>
        </div>
        <div>
          <input disabled="" value="option3" id="option-radio3" name="option-radio" type="radio">
          <label>Option three is disabled</label>
        </div>
      </fieldset>
      <fieldset>
        <legend>I am also legend</legend>
        <input id="checkbox1" type="checkbox">
        <label for="checkbox1">Check me out</label>
        <input id="checkbox2" type="checkbox">
        <label for="checkbox2">and/or check me out</label>
      </fieldset>
      <p>
        <button name="button" type="button">Button</button>
        <input value="Input Button" name="input" type="button">
        <input value="Input Submit" type="submit">
        <button name="submit2" type="submit">Submit</button>
        <input value="Input Reset" type="reset">
        <button name="reset2" type="reset">Reset</button>
        <button disabled="">Cancel</button>
      </p>
    </form>
    <p><code>ul</code> and <code>ol</code>:</p>
    <ul>
      <li>
        Unordered List item one
        <ul>
          <li>
            Nested list item
            <ul>
              <li>Level 3, item one</li>
              <li>Level 3, item two</li>
              <li>Level 3, item three</li>
              <li>Level 3, item four</li>
            </ul>
          </li>
          <li>List item two</li>
          <li>List item three</li>
          <li>List item four</li>
        </ul>
      </li>
      <li>List item two</li>
      <li>List item three</li>
      <li>List item four</li>
    </ul>
    <ol>
      <li>
        List item one
        <ol>
          <li>
            List item one
            <ol>
              <li>List item one</li>
              <li>List item two</li>
              <li>List item three</li>
              <li>List item four</li>
            </ol>
          </li>
          <li>List item two</li>
          <li>List item three</li>
          <li>List item four</li>
        </ol>
      </li>
      <li>List item two</li>
      <li>List item three</li>
      <li>List item four</li>
    </ol>
    <p><code>output</code>:</p>
    <form>
      <input step="any" type="number" name="a"> +
      <input step="any" type="number" name="b"> =
      <output for="a b" name="o"></output>
    </form>
    <p><code>pre</code>:</p>
    <pre>pre {
  display: block;
  padding: 7px;
  background-color: #F5F5F5;
  border: 1px solid #E1E1E8;
  border-radius: 3px;
  white-space: pre-wrap;
  word-break: break-all;
  font-family: Menlo, Monaco;
  line-height: 160%;
}</pre>
    <pre><samp>You are in an open field west of a big white house with a boarded
front door.
There is a small mailbox here.

</samp> <kbd>open mailbox</kbd>

<samp>Opening the mailbox reveals:
A leaflet.

</samp></pre>
    <br><br>
    <h4 id="tables"><a href="#tables">#</a> Tables</h4>
    <hr>
    <table>
      <caption>
        Tables can have captions now.
      </caption>
      <tbody>
        <tr>
          <th>Person</th>
          <th>Number</th>
          <th>Third Column</th>
        </tr>
        <tr>
          <td>Someone Lastname</td>
          <td>900</td>
          <td>
            Nullam quis risus eget urna mollis ornare vel eu
            leo.
          </td>
        </tr>
        <tr>
          <td><a href="#">Person Name</a></td>
          <td>1200</td>
          <td>
            Vestibulum id ligula porta felis euismod semper.
            Donec ullamcorper nulla non metus auctor
            fringilla.
          </td>
        </tr>
        <tr>
          <td>Another Person</td>
          <td>1500</td>
          <td>
            Vivamus sagittis lacus vel augue laoreet rutrum
            faucibus dolor auctor. Nullam id dolor id nibh
            ultricies vehicula ut id elit.
          </td>
        </tr>
        <tr>
          <td>Last One</td>
          <td>2800</td>
          <td>
            Morbi leo risus, porta ac consectetur ac,
            vestibulum at eros. Cras mattis consectetur
            purus sit amet fermentum.
          </td>
        </tr>
      </tbody>
    </table>
    <p id="table-summary">
      In the following table, characteristics are given in the
      second column, with the negative side in the left column and
      the positive side in the right column.
    </p>
    <table aria-describedby="table-summary">
      <caption>
        Characteristics with positive and negative sides
      </caption>
      <thead>
        <tr>
          <th id="n">Negative</th>
          <th>Characteristic</th>
          <th id="p">Positive</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td headers="n r1">Sad</td>
          <th id="r1">Mood</th>
          <td headers="p r1">Happy</td>
        </tr>
        <tr>
          <td headers="n r2">Failing</td>
          <th id="r2">Grade</th>
          <td headers="p r2">Passing</td>
        </tr>
      </tbody>
    </table>
    <table>
      <caption>
        Complex table with a
        <code>thead</code>, multiple
        <code>tbody</code>
        elements, and a
        <code>tfoot</code>.
      </caption>
      <thead>
        <tr>
          <th></th>
          <th>2008</th>
          <th>2007</th>
          <th>2006</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>Net sales</th>
          <td>$32,479</td>
          <td>$24,006</td>
          <td>$19,315</td>
        </tr>
        <tr>
          <th>Cost of sales</th>
          <td>21,334</td>
          <td>15,852</td>
          <td>13,717</td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <th>Gross margin</th>
          <td>$11,145</td>
          <td>$8,154</td>
          <td>$5,598</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <th>Gross margin percentage</th>
          <td>34.3%</td>
          <td>34.0%</td>
          <td>29.0%</td>
        </tr>
      </tfoot>
    </table>
    <footer>
      <p>
        See the
        <a href="https://www.w3.org/TR/html5/dom.html#palpable-content" target="_blank">Palpable Content spec.</a>
      </p>
    </footer>
  </section>
  <hr>
  <section>
    <header>
      <h3><a href="#embeds">#</a> Embeds</h3>
      <p>
        Elements <code>audio</code>, <code>canvas</code>,
        <code>embed</code>, <code>iframe</code>,
        <code>img</code>, <code>math</code>,
        <code>object</code>, <code>picture</code>,
        <code>svg</code>, <code>video</code> make up the
        <em>embedded content</em> category.
      </p>
    </header>
    <p>
      <code>audio</code>:
      <audio src="https://upload.wikimedia.org/wikipedia/commons/c/c7/What_hath_God_wrought.ogg" controls=""></audio>
      By Cqdx [<a href="https://creativecommons.org/licenses/by-sa/3.0">CC BY-SA 3.0 </a>],
      <a href="https://commons.wikimedia.org/wiki/File:What_hath_God_wrought.ogg">from Wikimedia Commons</a>.
    </p>
    <p>
      <code>embed</code>:
      
   </p>
    <p>
      <code>iframe</code>:
      <iframe></iframe>
    </p>
    <p>
      <code>img</code>:
      <img alt="Bill Murray" src="https://www.yiochukangsec.moe.edu.sg/images/Our%20Curriculum/Non%20Academic%20Programmes/CoCurricular%20Activities/Uniformed%20Groups/Red%20Cross%20Youth/R1.jpg">
    </p>
    <p><code>math</code>:</p>
    <math xmlns="http://www.w3.org/1998/Math/MathML">
      <mtable>
        <mtr>
          <mtd>
            <mtext>Quadratic Equation</mtext>
          </mtd>
          <mtd>
            <mrow>
              <mi>x</mi>
              <mo>=</mo>
              <mfrac>
                <mrow>
                  <mo>-</mo>
                  <mi>b</mi>
                  <mo>±</mo>
                  <msqrt>
                    <mrow>
                      <msubsup>
                        <mi>b</mi>
                        <mrow></mrow>
                        <mn>2</mn>
                      </msubsup>
                      <mo>-</mo>
                      <mn>4</mn>
                      <mi>a</mi>
                      <mi>c</mi>
                    </mrow>
                  </msqrt>
                </mrow>
                <mrow>
                  <mn>2</mn>
                  <mi>a</mi>
                </mrow>
              </mfrac>
            </mrow>
          </mtd>
        </mtr>
      </mtable>
    </math>
    <p>
      <code>picture</code>:
      <picture>
        <source srcset="https://www.fillmurray.com/240/300 2x,
                                https://www.fillmurray.com/120/150 1x">
        <img alt="Red Cross Youth" src="https://www.yiochukangsec.moe.edu.sg/images/Our%20Curriculum/Non%20Academic%20Programmes/CoCurricular%20Activities/Uniformed%20Groups/Red%20Cross%20Youth/R1.jpg">
      </picture>
    </p>
    <p>
      <code>svg</code>:
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" height="24" width="24" role="presentation">
        <path d="M19.199 24C19.199 13.467
            10.533 4.8 0 4.8V0c13.165 0 24 10.835 24 24h-4.801zM3.291
            17.415c1.814 0 3.293 1.479 3.293 3.295 0 1.813-1.485 3.29-3.301
            3.29C1.47 24 0 22.526 0 20.71s1.475-3.294 3.291-3.295zM15.909
            24h-4.665c0-6.169-5.075-11.245-11.244-11.245V8.09c8.727 0 15.909
            7.184 15.909 15.91z"></path>
      </svg>
    </p>
    <p>
      <code>video</code>:
      <video src="https://upload.wikimedia.org/wikipedia/commons/b/b8/Dwarf_hamsters_running_on_disc_2.ogv" controls=""></video>
    </p>
    <footer>
      <p>
        See the
        <a href="https://www.w3.org/TR/html5/dom.html#embedded-content" target="_blank">Embedded Content spec.</a>
      </p>
    </footer>
  </section>
  <hr>
</main>
<footer role="contentinfo">
  <p>
    Find this document on
    <a href="https://github.com/dbox/html5-kitchen-sink">GitHub</a>.
  </p>
</footer>
	
</details>


<style>
 .container { 
            /* CSS Multi-column Layout properties */
            column-count: 3;
            column-width: 160px; /* This is the key property */
            column-gap: 20px;
        }
        
        .card {
            break-inside: avoid; /* Prevents content from breaking across columns */
            page-break-inside: avoid; /* For older browsers */
            padding: 20px;
            margin-bottom: 20px;
            background-color: #f5f5f5;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
	
.yck-component .yck-table {
    border-collapse: collapse;
    max-width: 100%;
    margin-top: 1.6em;
    margin-bottom: var(--yck-space-s-l);
    font-size: var(--yck-step-0);
}

.yck-component .yck-th {
    background-color: #f2f2f2;
    text-align: left;
    border-bottom: 1px solid #ddd;
    text-transform: uppercase;
}

.yck-component .yck-th h4,
.yck-component .yck-th h5,
.yck-component .yck-th h6 {
    margin: 0 0 0.5em;
}

.yck-component .yck-td {
    border-bottom: 1px solid #ddd;
    max-width: 320px;
    word-wrap: break-word;
    line-height: 1.125em;
    padding-top: 0.5em;
    padding-bottom: 0.5em;
  }

.yck-component .yck-table tbody .yck-td p {
    margin-block: 0;
	line-height: 1.35rem;
    padding-bottom: 0.5em;
}
    
 .yck-component .yck-table tbody .yck-td p:last-child {
     padding-bottom: var(--yck-space-s-l);
 }
	
</style>