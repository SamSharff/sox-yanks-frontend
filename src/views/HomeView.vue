<script>
export default {
  data: function () {
    return {
      message: "Yankees are the Butts",
    };
  },
  created: function () {},
  methods: {},
};
</script>

<template>
  <div class="about">
    <h1>{{ message }}</h1>
    <p>
      Sox fans: It was a weird season. Take heart, and in the meantime take comfort in these Top 10 plays from the 2004
      ALCS between the Red Sox and Yankees.
    </p>
  </div>

  <div class="sr_share_wrap" style="overflow: auto">
    <table
      class="sr_share"
      id=""
      data-cols-to-freeze="1,2"
      data-toggle-class="pitch_sequence"
      data-toggle-text="Pitches"
      style="
        border-collapse: collapse;
        font-size: 0.83em;
        border: 1px sold #aaa;
        overflow: auto;
        margin-left: auto;
        margin-right: auto;
      "
    >
      <caption><strong>Top 10 Plays Table</strong></caption>
      <!-- <colgroup>
      <col />
      <col />
      <col />
      <col />
      <col />
      <col />
      <col />
      <col />
      <col />
      <col />
      <col />
      <col />
      <col />
    </colgroup> -->
      <thead>
        <tr>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">Gm#</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">Inn</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">Score</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">Out</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">RoB</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">Pit(cnt)</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">R/O</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">@Bat</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">Batter</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">Pitcher</th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">cWPA</th>
          <th
            scope="col"
            data-filter="1"
            data-name="cLI"
            style="background-color: #ddd; border: 1px solid #aaa; padding: 2px"
          >
            cLI
          </th>
          <th scope="col" style="background-color: #ddd; border: 1px solid #aaa; padding: 2px">Play Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/NYA/NYA200410200.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 7
            </a>
          </th>
          <td csk="7005" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">t1</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">tied 0-0</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=NYA200410200-5-post"
            csk="1.001"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            1--
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=NYA200410200-5-post"
            csk="1"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            1&nbsp;(0-0)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">RR</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">BOS</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/o/ortizda01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              David Ortiz
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/b/brownke01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Kevin Brown
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">8.74%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">65.83</td>
          <td csk="23.005" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.youtube.com/watch?v=dyFhFtLsa-k&feature=share&utm_source=EJGixIgBCJiu2KjB4oSJEQ"
              target="_blank"
            >
              Home Run (Fly Ball); Ramirez Scores
            </a>
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/NYA/NYA200410200.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 7
            </a>
          </th>
          <td csk="7014" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">t2</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">ahead 2-0</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">1</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=NYA200410200-14-post"
            csk="3.111"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            123
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=NYA200410200-14-post"
            csk="1"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            1&nbsp;(0-0)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">RRRR</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">BOS</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/d/damonjo01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Johnny Damon
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/v/vazquja01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Javier Vazquez
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">7.58%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">153.33</td>
          <td csk="23.014" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.youtube.com/watch?v=IAgMBIu6iVk&feature=share&utm_source=EJGixIgBCJiu2KjB4oSJEQ&t=1"
              target="_blank"
            >
              Home Run (Fly Ball); Millar Scores; Mueller Scores; Cabrera Scores
            </a>
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/NYA/NYA200410190.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 6
            </a>
          </th>
          <td csk="6029" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">t4</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">ahead 1-0</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=NYA200410190-29-post"
            csk="2.011"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            12-
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=NYA200410190-29-post"
            csk="5"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            5&nbsp;(1-2)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">RRR</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">BOS</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/b/bellhma01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Mark Bellhorn
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/l/liebejo01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Jon Lieber
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">5.54%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">65.12</td>
          <td csk="23.029" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.youtube.com/watch?v=YkXPxy_e1sI&feature=share&utm_source=EJGixIgBCJiu2KjB4oSJEQ&t=1"
              target="_blank"
            >
              Home Run (Fly Ball); Varitek Scores; Cabrera Scores
            </a>
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/BOS/BOS200410180.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 5
            </a>
          </th>
          <td csk="5126" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">b14</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">tied 4-4</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=BOS200410180-126-post"
            csk="2.011"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            12-
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=BOS200410180-126-post"
            csk="10"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            10&nbsp;(2-2)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">R</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">BOS</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/o/ortizda01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              David Ortiz
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/l/loaizes01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Esteban Loaiza
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">4.01%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">78.89</td>
          <td csk="20.126" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.youtube.com/watch?v=gu-m2CYHW4Y&feature=share&utm_source=EJGixIgBCJiu2KjB4oSJEQ"
              target="_blank"
            >
              Single to CF (Line Drive); Damon Scores; Ramirez to 2B
            </a>
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/BOS/BOS200410180.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 5
            </a>
          </th>
          <td csk="5051" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">t6</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">down 2-1</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=BOS200410180-51-post"
            csk="3.111"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            123
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=BOS200410180-51-post"
            csk="3"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            3&nbsp;(1-1)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">RRR</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">NYY</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/j/jeterde01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Derek Jeter
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/m/martipe02.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Pedro Martinez
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">3.80%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">77.66</td>
          <td csk="21.051" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.youtube.com/clip/UgkxqIqlJEFEDV23H8UJ9fGimm5eDtgf_xgg?utm_source=EJGixIgBCJiu2KjB4oSJEQ"
              target="_blank"
            >
              Double to RF (Line Drive); Posada Scores; Sierra Scores; Cairo Scores; Jeter to 3B/Adv on throw
            </a>
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/NYA/NYA200410190.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 6
            </a>
          </th>
          <td csk="6012" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">t2</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">tied 0-0</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">1</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=NYA200410190-12-post"
            csk="3.111"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            123
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=NYA200410190-12-post"
            csk="5"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            5&nbsp;(0-2)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">OO</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">BOS</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/b/bellhma01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Mark Bellhorn
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/l/liebejo01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Jon Lieber
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">3.48%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">96.92</td>
          <td csk="2.012" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.youtube.com/clip/UgkxRqbkDbZtZXg1v3VfKQUbq2DjwyWq4EjZ?utm_source=EJGixIgBCJiu2KjB4oSJEQ"
              target="_blank"
            >
              Ground Ball Double Play: 2B-SS-1B
            </a>
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/BOS/BOS200410160.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 3
            </a>
          </th>
          <td csk="3042" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">t4</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">tied 6-6</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">1</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=BOS200410160-42-post"
            csk="2.011"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            12-
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=BOS200410160-42-post"
            csk="2"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            2&nbsp;(1-0)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">RRR</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">NYY</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/s/sheffga01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gary Sheffield
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/l/leskacu01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Curt Leskanic
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2.95%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">46.45</td>
          <td csk="23.042" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            Home Run (Fly Ball); Cairo Scores; Rodriguez Scores
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/NYA/NYA200410130.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 2
            </a>
          </th>
          <td csk="2046" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">b6</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">ahead 1-0</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">1</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=NYA200410130-46-post"
            csk="1.001"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            1--
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=NYA200410130-46-post"
            csk="4"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            4&nbsp;(1-2)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">RR</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">NYY</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/o/olerujo01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              John Olerud
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/m/martipe02.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Pedro Martinez
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2.56%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">30.25</td>
          <td csk="23.046" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            Home Run (Line Drive); Posada Scores
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/NYA/NYA200410120.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 1
            </a>
          </th>
          <td csk="1068" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">t8</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">down 8-5</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=NYA200410120-68-post"
            csk="2.101"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            1-3
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=NYA200410120-68-post"
            csk="5"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            5&nbsp;(3-1)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">RR</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">BOS</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/o/ortizda01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              David Ortiz
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/g/gordoto01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Tom Gordon
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2.44%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">42.61</td>
          <td csk="22.068" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            Triple to LF (Fly Ball); Mueller Scores; Ramirez Scores
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/NYA/NYA200410190.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Gm 6
            </a>
          </th>
          <td csk="6027" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">t4</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">tied 0-0</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=NYA200410190-27-post"
            csk="1.100"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            --3
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=NYA200410190-27-post"
            csk="10"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            10&nbsp;(3-2)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">R</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">BOS</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/v/varitja01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Jason Varitek
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/players/l/liebejo01.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              Jon Lieber
            </a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">2.42%</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">62.06</td>
          <td csk="20.027" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            Single to CF (Line Drive); Millar Scores
          </td>
        </tr>
        <tr>
          <th scope="row" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a
              href="https://www.baseball-reference.com/boxes/NYA/NYA200410190.shtml?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
            >
              *Gm 6
            </a>
          </th>
          <td csk="6027" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">b8</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">down 2-4</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">1</td>
          <td
            data-endpoint="/tools/def.cgi?html=1&amp;game-event=NYA200410190-27-post"
            csk="1.100"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            1--
          </td>
          <td
            data-endpoint="/tools/pitch.cgi?html=1&amp;game-event=NYA200410190-27-post"
            csk="10"
            style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap"
          >
            6&nbsp;(2-2)
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">O</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">NYY</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a href="https://www.baseball-reference.com/players/r/rodrial01.shtml">Alex Rodriguez</a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            <a href="https://www.baseball-reference.com/players/a/arroybr01.shtml">Bronson Arroyo</a>
          </td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">-</td>
          <td style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">-</td>
          <td csk="20.027" style="border: 1px solid #ccc; padding: 2px 3px 2px 2px; white-space: nowrap">
            Interference by Batter: P unassisted; Jeter stays at 1B
          </td>
        </tr>
      </tbody>
    </table>
    <div id="credit_top_plays" class="sr_share" style="font-size: 0.83em; margin-left: 10%; margin-right: 10%">
      <br />
      *This (dis)honorable mention (the infamous "A-Rod ridiculously slaps ball from Arroyo's glove" play) is not part
      of the original BR data set. The author has included it here as an anecdotal 'Top 10 Play' based on exactly zero
      data, but in recognition of the weight it carries for Sox fans in our eternal torch of "Ugh" for A-Rod and this
      Yankees team.
      <br />
      <br />
      Provided by:
      <a
        href="https://www.sports-reference.com/sharing.html?utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool"
      >
        Baseball-Reference.com
      </a>
      -
      <a
        href="https://www.baseball-reference.com/postseason/2004_ALCS.shtml?sr&amp;utm_source=direct&amp;utm_medium=Share&amp;utm_campaign=ShareTool#top_plays"
      >
        View Original Table
      </a>
      <br />
      Generated 9/19/2022.
    </div>
  </div>
</template>

<style>
body {
  background-color: rgba(208, 54, 54, 0.693);
}
</style>
