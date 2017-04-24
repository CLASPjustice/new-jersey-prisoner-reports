# New Jersey Prisoner Reports
> Help us code anonymous prisoner testimony

**New Jersey Prisoner Reports** is a public, online database of anonymous prisoner testimony. Originally a report published by the **American Friends Service Committee**'s *Prison Watch Project*, [@billimarie](https://www.github.com/billimarie) of **CLASP** has transcribed the data into a searchable web app ([**CLASP: New Jersey Prisoner Reports**](https://www.CLASPjustice.com/prisoner-reports)).

## Instructions

### 1. Open the original report

Official CLASP volunteers: ["From The Inside Out" (.doc)](https://drive.google.com/drive/u/0/folders/0B9cqp4PZ4Q09eWxUU0stT2JUVm8). For everyone else: ["From The Inside Out" (.pdf)](https://www.afsc.org/sites/afsc.civicactions.net/files/documents/From%20the%20Inside%20Out%20%232.pdf)

### 2. Copy an individual testimony

<img src="https://github.com/CLASPjustice/new-jersey-prisoner-reports/blob/master/images/new-jersey-prisoner-reports_tutorial_01.gif" width="600px" />

### 3. Paste and reformat into HTML

Open [New Jersey Prisoner Reports (.html)](/index.html). Paste and reformat the testimony.

<img src="https://github.com/CLASPjustice/new-jersey-prisoner-reports/blob/master/images/new-jersey-prisoner-reports_tutorial_02.gif" width="600px" />

Essentially, you will be inputing data into a list. Follow the coding standard:

```
<li class="report" data-id="4">
 <h3 class="prisoner">K.</h3>
 <h3 class="prison">East Jersey State Prison</h3>
 <h3 class="date">01/11/17</h3>
 <ul class="issue-tags">
  <li class="issue">Physical Assault</li>
  <li class="issue">Environmental Conditions</li>
 </ul>
 <p class="testimony">"In 2013...I was attacked by a cellmate. He threw hot water on me which caused serious burns. After the hot water was thrown on me, I was taken to a hospital outside the prison. [When I returned] I was placed in a detention cell...an isolated 'dry cell' in the prison infirmary. In this cell, there was no bed, only a 2 or 3 inch mattress on the floor. There was no other furniture. As for fixtures, there was a sink connected to a toilet, but the toilet was flushed from outside the cell. The cell itself was filthy, with dry feces smeared on the walls. My teeth were chattering and I was trembling, that's how cold it was. Eventually, I was given two sheets and a blanket which provided little protection from the cold."</p>
</li>
```

### 4. Repeat. Don't forget to save!

<img src="https://github.com/CLASPjustice/new-jersey-prisoner-reports/blob/master/images/new-jersey-prisoner-reports_tutorial_03.gif" width="600px" />
