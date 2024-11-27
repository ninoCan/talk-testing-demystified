<style>
  :root {
    --r-background-color: rgb(33, 34, 44);
    --grey: rgb(65, 69, 88);
    --white: rgb(248, 248, 242);
    --blue: rgb(106, 154, 224);
    --cyan: rgb(128, 255, 234);
    --green: rgb(138, 255, 128);
    --r-heading-color: rgb(255, 202, 128);
    --pink: rgb(255, 128, 191);
    --r-main-color: rgb(149, 128, 255);
    --red: rgb(255, 149, 128);
    --yellow: rgb(255, 255, 128);
     #FF80BF;
  }
  .no-wrap {
    white-space: nowrap;
  }
  .larger {
    font-size: larger;
  }
  .small {
    font-size: 90%;
  }
  .small-column {
    float: left;
    width: 25%;
  }
  .third-column {
    float: left;
    width: 33%;
  }
  .column {
    float: left;
    width: 50%;
  }
  .large-column {
    float: left;
    width: 75%;
  }
  h1 {
    font-weight: 100;
  }
  img {
    loading: lazy;
  }
  .gif {
    height: 240px;
    width: 360px;
  }
  li {
    line-height: 2em;
  }
  emph {
    color: var(--red);
  }
  .lc {
    text-transform: lowercase;
  }
  .tips {
    padding: 0; /* Reset padding for the list */
    margin: 0;
  }
  .tips li {
    list-style: none; /* Remove default bullets */
    position: relative; /* Allow positioning of the pseudo-element */
    padding-left: 75px; /* Space for "TIP:" */
  }
  .tips li::before {
    content: "TIP:"; /* Add the "TIP:" text */
    position: absolute;
    left: 0;
    font-style: italic; /* Style as emphasized text */
    font-weight: bold;
    color:var(--green)
  }
  .rounded {
    border-radius: 5%;
  }
  .repo {
    padding: 0; /* Reset padding for the list */
    margin: 0;
  }
  .repo li {
    list-style: none; /* Remove default bullets */
    position: relative; /* Allow positioning of the pseudo-element */
    padding-left: 75px; /* Space for "TIP:" */
  }
  .repo li::before {
    content: "REPO:"; /* Add the "TIP:" text */
    position: absolute;
    margin-left: -30px;
    left: 0;
    font-style: italic; /* Style as emphasized text */
    font-weight: bold;
    color:var(--pink)
  }
  .sd {
    padding: 0; /* Reset padding for the list */
    margin: 0;
  }
  .sd li {
    list-style: none; /* Remove default bullets */
    position: relative; /* Allow positioning of the pseudo-element */
    padding-left: 75px; /* Space for "TIP:" */
  }
  .sd li::before {
    content: "SLIDES:"; /* Add the "TIP:" text */
    position: absolute;
    margin-left: -40px;
    left: 0;
    font-style: italic; /* Style as emphasized text */
    font-weight: bold;
    color:var(--green)
  }
  .r-stack {
    display: grid;
    grid-template-rows: 100%;
  }
</style>


# <emph class="no-wrap">Testing Demystified:</emph>
<h2><em>the boring,</em></h1>
<h2><strong style="color: var(--r-main-color);">the hard,</strong><h1>
<h2 style="text-decoration: underline; color: var(--green)">the practical</h1>

---

# About Me

<div class="column" style="margin-top: -90px;">
<h3 style="margin-top: 130px">Anto"nino" Cangialosi</h3>
Big Data Engineer<br/>
@ Agile Lab

<i class="fa fa-github fa-lg"> </i>
<i class="fa fa-gitlab fa-lg"> </i>
<i class="fa fa-slack fa-lg"> ninoCan</i><br/>
<i class="fa fa-linkedin"> antonino-cangialosi</i>

</div>

<div class="column">
<img style="width: 160px" src="https://images.credly.com/size/340x340/images/8b8ed108-e77d-4396-ac59-2504583b9d54/cka_from_cncfsite__281_29.png">
<img style="width: 140px" src="https://images.credly.com/size/340x340/images/2d613ff8-8879-430b-b2d8-925fa29785e8/image.png">
<img style="width: 130px" src="https://images.credly.com/size/340x340/images/f28f1d88-428a-47f6-95b5-7da1dd6c1000/KCNA_badge.png">
<img style="width: 190px" src="https://www.datacamp.com/statement-of-accomplishment/badge/track/86369ef15d2722bc789beeb26e9a5f28c68558d7.png">
<img style="width: 190px" src="https://www.datacamp.com/statement-of-accomplishment/badge/track/e265d97f60368099e8c955bf28b08b306f00a506.png">
</div>

---

<h2 style="white-space: nowrap">Testing Misconceptions</h1>
<div class="column">
<img class="gif rounded" src="https://i.giphy.com/lJnAXeJO8tE7E37mxq.webp">
</div>
<div class="column">
<img class="gif rounded" src="https://media4.giphy.com/media/3o7btPCcdNniyf0ArS/200.gif">
</div>
<div>
<img class="gif rounded" src="https://media.tenor.com/IXY41b20EwMAAAAM/time-speed.gif"/>
</div>

---

## <emph>Question:</emph> How many of you practice testing on their deliverables?

---

## <emph>Eye-ball tests</emph>
## are the most common
## way of testing

---

<h2>Blueprint &amp; documentation</h2>
<div class=column>
<img class="gif rounded" src="https://media0.giphy.com/media/9xmjP6FkdINCA6Ucp4/200.gif ">
</div>
<div class=column>
<ul style="margin: 30px 0px;">
  <li>Freeze requirements</li>
  <li>Example of usage</li>
  <li>Enable repeatability</li>
</ul>
</div>

---

<h2>why should we <emph class="larger;">prepare</emph> tests?</h2>

<ul>
  <li>enable rapid <emph class="larger">rework</emph></li>
  <li><emph>validate</emph> the work</li>
  <li>remove the <emph class="larger">ego</emph></li>
</ul>

---

# <strong style="color: var(--r-main-color);">Hard</strong>

---

## Symptoms

<div class="column">
<img src="https://miro.medium.com/v2/resize:fit:487/1*_te2Z2DGMmbwu3plPjlB8g.jpeg" class="gif rounded">
</div>
<div class="column">
<ul>
  <li>Different <emph>layers</emph></li>
  <li>Opaque <emph>jargon</emph></li>
  <li class="no-wrap"><emph>Not everything</emph> is testable</li>
  <li class="no-wrap"><emph>Mutability</emph> creates <emph>side-effects</emph></li>
</ul>
</div>

---

# <emph>Tests layers</emph>

<div class="third-column">
  <h2 style="color: var(--pink);">Unit</h2>
<ul style="color: var(--pink);">
  <li>finer detail</li>
  <li>isolation</li>
  <li>faster</li>
  <li>brittle</li>
</ul>
</div>
<div class="third-column">
  <h2 style="color: var(--green);">Integration</h2>
<ul style="color: var(--green);">
  <li>interfaces</li>
  <li>behavioural</li>
  <li>fast/slow</li>
  <li>durable</li>
</ul>
</div>
<div class="third-column">
  <h2 style="color: var(--cyan)">End-to-end</h2>
<ul style="color: var(--cyan);">
  <li>processes</li>
  <li>enseble</li>
  <li>slow</li>
  <li>error-prone</li>
</ul>
</div>

---

# <emph>Question:</emph> What is the right proportion?

---


<div class="third-column"><img style="height:180px;" style="height: 240px;" src="slidedeck/assets/test-shapes/reverse-pyramid.svg"></div>
<div class="third-column"><img style="height:180px;" src="slidedeck/assets/test-shapes/pyramid.svg"></div>
<div class="third-column"><img style="height:180px;" src="slidedeck/assets/test-shapes/diamond.svg"></div>
<div>

#

<!-- <span style="opacity: 0; margin-top: -100px;">This is needed to correctly render the title!</span> -->
  <h2> It depends!</emph> </h2>
</div>
<div class="third-column"><img src="slidedeck/assets/test-shapes/ocd-dev.svg"></div>
<div class="third-column"><img src="slidedeck/assets/test-shapes/true-diamond.svg"></div>
<div class="third-column"><img src="slidedeck/assets/test-shapes/summer-intern.svg"></div>

---

# <em>Boring</em>

---

## <span style="color: var(--green);">Feature</span> not a<emph> bug</emph>
<img src="https://i.imgflip.com/9beamx.jpg"
style="clip-path: inset(2% 2% 2% 2% round 5%);"
/>

---

<div class="large-column">

## What is a <emph>test suite</emph>? <i class="fa-solid fa-cards"></i>

</div>

<div class="small-column">
<img class="rounded" src="https://img.freepik.com/premium-vector/hand-drawn-playing-cards-icon-sticker-style-vector-illustration_755164-11343.jpg?w=740" style="width:240px; margin-top: -20px" />
</div>

A <emph>Test Case</emph> is just a set of boolean fuctions
```
class TestSuite:

  func testCase1 {
    assert actual == expected
  }

  func testCase2 {
    assert actual == expectation_1
    assert actual.part == expectation_2
  }

```
<ul class="tips">
  <li>DON'T use too many expectations<br></li>
  <li>cluster similar behaviour</li>
</ul>

---

## The 3 <emph class="larger">A</emph>s framework

<div class="column">
  <ul>
    <li>
      <emph class="larger">A</emph><emph class="small">RRANGE</emph><br>
      &nbsp;prepare the elements
    </li>
    <li>
      <emph class="larger">A</emph><emph class="small">CT</emph><br>
      &nbsp;let the music play
    </li>
    <li>
      <emph class="larger">A</emph><emph class="small">SSERT</emph><br>
    </li>
  </ul>
</div>
<div class="column">

```
class TestSuite:

  func testCase {
    # Arrange
    under_test = greet
    expected = "Hello, World!"

    # Act
    actual = under_test()

    # Assert
    assert actual == expected
  }

```

</div>

  <ul class="tips">
    <li>call the subject <strong>underTest</strong></li>
  </ul>

---

## Test Doubles

These are the essential components of each tests

<img src="https://i.imgur.com/40VJYpl.jpeg" style="width: 40%; clip-path: inset(6% 2% 2% 2% round 5%); z-index:0"></img>

<img src="slidedeck/assets/arrows/arrow.svg" style="margin-left: -60px; margin-top: -150px; z-index: 2; position: relative;"></img>

---

## Test doubles: <emph class="larger">Dummy</emph>

<div class="column">
  <img src="https://media1.giphy.com/media/5xrkJe3IJKSze/200.gif" class="gif rounded">
  <br>
  <ul class="li">
    <li>Fill in static parameters</li>
  </ul>
</div>
<div class="column">

<br>

```
# Arrange
under_test = greet
name_dummy = "John"
expected = "Hello, $name_dummy"

# Act
actual = under_test(name_dummy)

# Assert
assert actual == expected
```

</div>

<ul class="tips">
  <li> use in both arrange and act phase</li>
</ul>

---

## Test doubles: <emph class="larger">Stub</emph>

<div class="column">

<pre class="rounded" style="block-size: 475px;">
<code class="language-python"># Arrange
under_test = Car
t_dummy = 15
a_stub = Rolling_mat(
  acceleration = "2 m/s^2"
)
expected = (
  a_stub.value * t_dummy^2 / 2
)

# Act
actual = under_test.accelerate(
  time = t_dummy,
  travel_on = a_stub
).get_travelled_distance

# Assert
assert actual == expected
</code></pre>

</div>
<div class="column">
  <img src="https://media0.giphy.com/media/3oEjI8ne0quKfqgJaw/200.gif" class="gif rounded" style="height: 180px;">
  <br>
  <ul class="li">
    <li class="small">Simulate external systems</li>
    <li class="small">Passive behaviour</li>
    <li class="small">Document possible inputs</li>
  </ul>
</div>

---

## Test Doubles: <emph class="larger">Mock</emph>

<div class="column">
  <img class="gif rounded" style="clip-path: inset(2% 10% 10% 2% round 5%)" src="https://media4.giphy.com/media/3BPHdmXcdrgTS/200.gif" alt="">
  <ul>
    <li class="small">Substitute internal deps</li>
    <li class="small">Active behaviour</li>
    <li class="small">Freeze assumptions</li>
  </ul>
</div>

<div class="column">
  <pre style="
   block-size: 445px;
   width: fit-content;"
  >
    <code class="language-python" style="overflow: visible;"># Arrange
under_test = PaymentService
message_dummy = "Insufficent funds"
url_stub = "https://external.service"
request_mock = Mock.get(url_stub)
  .return_value(
    code=404,
    message=message_dummy
  )
sum_dummy = "1.000.000€"
# Act
actual = PaymentService.withdraw(
  request_broker = request_mock,
  sum_dummy
)
# Assert
assert actual.response_code == 404
</code></pre>
</div>

---

## Test Doubles: <emph class="larger">Patch</emph>

<div class="column">

<pre class="rounded" style="
   margin-left: -100px;
   block-size: 420px;
   width: fit-content;"
  >
<code style="overflow: visible;"># Arrange
under_test = FileHandler
path_stub = './a/file/path/'
file_stub = """A file containing
multiple lines """
input_dummy = "new line"
expected = file_stub + input_dummy
# Act
Patch("FileSystemLibrary.open")
  .return_value(file_stub)
actual = underTest.append(
  path = path_stub,
  new = input_dummy
)
# Assert
assert actual == expected
</code></pre>

</div>
<div class="column">
  <img src="https://media4.giphy.com/media/NWpTZunsRRaJor5KD1/200.gif" class="rounded" style="height: 180px;
  clip-path: inset(5% 22% 0% 21% round 5%);">
  <br>
  <ul class="li">
    <li class="small">Over-ride internal deps</li>
    <li class="small">Active behaviour</li>
    <li class="small">Not always allowed</li>
  </ul>
</div>

---

## Test Doubles: <emph class="larger">Spy</emph>

<div class="column">
  <pre style="width: fit-content; height: 470px;">
    <code style="overflow: visible;">#Arrange
under_test = RegistrationService
data_dummy = {
  name: "Alice",
  email: "alice@example.com"
}
mailerService = Spy()
mailerService.spyOn("send")
expected = "Mail sent"
# Act
expected = under_test(data_dummy)
# Assert
assert result == expected
assert mailerService.send
  .called_once_with(
  "Welcome, Alice",
  "alice@example.com"
)
    </code>
  </pre>
</div>
<div class="column">
<img src="https://media4.giphy.com/media/Q7hsmwo7xDqQ8/200.gif" class="gif rounded"></img>
<ul>
  <li class="small">Substitute deps</li>
  <li class="small">Introspect behaviour</li>
  <li class="small">Control implementation</li>
</ul>
</div>
<ul class="tips">
  <li class="small no-wrap">Can be queried in expectations</li>
</ul>

---

## Test Doubles: <emph class="larger">Fake</emph>



<div class="column">
  <img src="https://media2.giphy.com/media/foaTaX2k4mZroV7xHj/200.gif"
  class="gif rounded"
>

  <ul>
    <li class="small">Functional replacement</li>
    <li class="small">Complex logic required</li>
    <li class="small">Simulate real loads</li>
  </ul>
</div>
<div class="column">
  <pre style="width: fit-content;
  height: 450px;
  "><code class="language-python" style="overflow: visible;">#Arrange
under_test = UserRegistrationService
data_fake = new Faker({
  "name": generate_name(),
  "birthday": generate_date(),
  "email": generate_mail()
})
db_fake = sqlite.connect(":memory:")
# Act
expected = under_test(data_fake)
# Assert
assert actual.exit_code = 0
query_result = db_fake.execute(
  """SELECT count(*)
  FROM users;"""
)
assert query == 1
  </code></pre>
</div>

---

## <emph>It a continuum!</emph>


<figure style="background-color: #A5D8FF; width: fit-content; display: inline-block;">
  <img src="https://learn.microsoft.com/en-us/archive/msdn-magazine/2007/september/images/cc163358.fig02.gif" style="margin-left: 40%vp">
</figure>
  <figcaption style="font-size: 60%; color: #268BD2;">Source: <a href="">Microsoft Learn Challenge</a></figcaption>

---

# <span style="text-decoration: underline; color: var(--green)">Practical</span>

---

<div>
<img src="https://media0.giphy.com/media/IGlZHF3OEWtbrTNiPX/200.gif" class="gif rounded"></img>
</div>

## <emph>ONE acronym to rule them all</emph>

  <div class="r-hstack justify-center">
<div
  data-id="box2"
  data-auto-animate-delay="0.1"
  style="background: var(--green); width: 150px; height: 100px;
  margin: 10px; align-content: center"
>

**TDD**
</div>

<div
  data-id="box2"
  data-auto-animate-delay="0.1"
  style="background: var(--r-heading-color); width: 150px; height: 100px;
  margin: 10px; align-content: center"
>

**tDd**
</div>
<div
  data-id="box2"
  data-auto-animate-delay="0.1"
  style="background: var(--yellow); width: 150px; height: 100px;
  margin: 10px; align-content: center"
>

**TDd**
</div>
  <div class="r-hstack justify-center">

<div
  data-id="box2"
  data-auto-animate-delay="0.1"
  style="background: var(--cyan); width: 150px; height: 100px;
  margin: 10px; align-content: center"
>

**&lt;T>DD**
  </div>

---

<h2 class="larger" style="color: var(--green);">
  <emph class="larger">T</emph>est-<emph class="larger">D</emph>riven <emph class="larger">D</emph>evelopment
</h2>

<span class="small" style="color: var(--r-heading-color);">
Write tests before even starting writing a single line of code!</span>
<h2 style="color: var(--red);">Red</span> <span style="color: var(--green);">Green</span> <span style="color: #6A9AE0;">Refactor</h2>
<div class="column">
  <ul style="color: var(--r-heading-color);">
    <li class="small">Write a test case</li>
    <li class="small">Check it fails</li>
    <li class="small">Implement feature</li>
    <li class="small">Make it pass</li>
    <li class="small">Optimize</li>
  </ul>
</div>
<div class="column" style="margin-top: 50px;">
  <img src="https://media4.giphy.com/media/xl2GGfiBBN0EE/200.gif" class="gif rounded">
</div>

---

<h2 style="color: var(--green);">
  <emph class="lc larger">t</emph><span class="lc">he</span> <emph class="larger">D</emph>EBUGGER <emph class="lc larger">D</emph><span class="lc">rives</span>
</h2>

<span class="small" style="color: var(--r-heading-color);">
Setup a minimal working runtime to start a debugger session!
<br>
<br>
<div class="column">
  <ul>
    <li>Write a minimal entrypoint</li>
    <li>Start the debugger/REPL</li>
    <li>Explore and write tests</li>
    <li>Reach the goal</li>
    <li>Optimize</li>
  </ul>
</div>
<div class="column">
  <img
    src="https://preview.redd.it/bmv21s0ws4zz.png?width=1080&crop=smart&auto=webp&s=92040429ee492ee0dae21192e869543d5f2432ad"
    class="rounded"
    style="height: 350px;">
</div>
</span>
<ul class="tips">
  <li>Save progress as Unit test</li>
</ul>

---

<h2 style="color: var(--green);">
  <emph class="larger">T</emph>est-<emph class="larger">D</emph>riven <emph class="lc larger">d</emph><span class="lc">esign</span>
</h2>

<span class="small" style="color: var(--r-heading-color);">
Think about tests before even writing anything.
<span>

<div class="column">
  <h3 class="no-wrap" style="color: var(--blue);">
  Behavior Driven Development
  </h3>
  <ul>
    <li class="small">Create a narrative</li>
  </ul><br>
  <pre>
  <code class="language-gherkin;">
  AS A: sale representative
  I WANT: to create a quote quickly
  SO THAT: the deal can be closed
  - - -
  SCENARIO: dashboard
  GIVEN I select a range
  WHEN I right-click
  THEN the dashboard should display
       cross-sell info</code>
  <pre>
</div>
<div class="column">
  <pre style="margin-left: 10px; width: fit-content; height: 320px;">
    <code class="language-python" style="overflow=visible;">class DashboardSuite:
  func should_return_cross_sell_info {
    # Arrange
    dashboard = load_with_mock_data()
    range_stub = {
      start: '2024-11-01',
      end: '2024-11-27' }
    # Act
    dashboard.select(range_stub)
    dashboard.right_click()
    expected = dashboard.display()
    # Assert
    assertVisible expected.cross_sell
  }</code>
  </pre>
  <ul>
    <li class="small">That devs can translate</li>
  </ul>
</div>

<ul class="tips">
  <li>Cross functional, brings in all stake-holders</li>
</ul>

---

<h2>
  <emph class="larger">&lt;T></emph>ype-<emph class="larger">D</emph>riven <emph class="larger">D</emph>evelopment
</h2>

Think about signatures first!

<div class="column">
  <ul>
    <li class="small">Functional friendly</li>
    <li class="small">Compiler catch bugs</li>
  </ul>
  <ul class="tips">
    <li class="small">Null-safety</li>
    <li class="small">LLM-prototyped tests</li>
  </ul>
</div>
<div class="column">
<img src="https://media1.giphy.com/media/l3q2MDnkLri1t7i5a/200.gif" alt="" class="gif rounded"></div>


---

# Thank you!

<ul class="repo small">
  <li class="no-wrap small">https://www.github.io/ninocan/talk-testing-demystified/</li>
</ul>
<ul class="small sd">
  <li class="small">https://ninocan.github.io/talk-testing-demystified/</li>
</ul>

<div class="column">
<iframe src="https://ninocan.github.io/talk-testing-demystified" width="100%" height="360" frameborder="0" scrolling="no"></iframe>
  <embed
    class="rounded"
    src="https://github.com/ninoCan/">
  </embed>
</div>
<div class="column"><img class="rounded" src="slidedeck/assets/qr-code.svg" style="height: 360px; margin-top: -1px;"></img></div>
