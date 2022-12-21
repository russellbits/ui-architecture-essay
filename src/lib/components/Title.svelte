<script></script>

<section id="title">
  <div id="title_line_1">User Interface</div>
  <div id="title_line_2">Architecture</div>
  <div id="byline">by Russell Warner</div>
</section>

<style>
section#title {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 1em;
  margin-top: 108px;
}

#title_line_1 {
  grid-column: 2 / 9;
  font-size: 57px;
  text-transform: uppercase;
  line-height: 12px;
}

#title_line_2 {
  grid-column: 2 / 9;
  font-size: 60px;
  font-weight: bold;
  line-height: 73px;
  text-transform: uppercase;
}

#byline {
  grid-column: 5 / 9;
  font-size: 24px;
  font-weight: 400;
  text-align: right;
}
</style>
