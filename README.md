---
title: Studies - Root
tags: studies, programação
use: Documentation
languages: NULL
dependences: NULL
---

> [!INFO] 
> The links are built for the obsidian branch, i was working in main but now i'll split correctly and after that update all the inter document links 

---

> This is a list of interesting documents gathered during development studies
# The Big Picture

This repo is divided in two branches, [main](https://github.com/see7e/programing-studies) has common links and [obsidian](https://github.com/see7e/programing-studies/tree/obsidian) links follow a Zettelkasten adapted model along with Obsidian to map the network of documents. If you want to set up in you computer, [click here](./obisidian_init.md).

<details>
	<summary>If you want to know the history, click here.</summary>
	<p>
		I've started using Obsidian and found very userfull to see how my brain works, and all its connections. Sometime after stumbled with the Zettelkasten method, it fits right into the philosophy of the program.</p>
    <p>
	    But the problem is that all my information was divided in a big folder structure, so I took my time and started thinking about how to conciliate both methods, PARA and Zettel.
    </p>
    <p>
	    The links, the special <code>[[]]</code> Obsidian type and the common <code>[](./path/to/file)</code>. The first one don't work in GitHub, and the second one if is a web url Obsidian won't link the way we expect. So what I will do/did is put altogether in one folder, and set <code>.gitignore</code> for exclude the independent sub-folders which are individual repositories, and with that Git won't create a mess during the commits and pushes.
    </p>
</details>

</br>

![Galaxy|500](./src/img/prog-galaxy.png)


# [List of Documents](./DIRECTORY.md)

## Progress


```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#23375E',
      'primaryTextColor': '#FFF',
      'primaryBorderColor': '#7C0000',
      'lineColor': '#F8B229'
    }
  }
}%%

gantt
	title My Roadmap
    dateFormat  DD-MM-YYYY

    section Courses
    CS50 - C                    :done, c1, 02-05-2023, 28-06-2023
    CS50 - Python               :done, c2, after c1, 03-07-2023
    CS50 - SQL                  :done, c3, after c2, 7d
    CS50 - HTML, CSS, JS        :done, c4, after c3, 7d
    CS50 - Flask                :done, c5, after c4, 7d
    CS50 - Final Project        :done, c6, after c5, 14-08-2023
    42-Common Core              :milestone, 42, 02-10-2023, 0d

    section Other
    Python RoadMap              :active, a1, 02-05-2023, 80d
    SQL RoadMap|PSQL|PostGIS    :active, after a1, 60d
    OpenPyXL                    :done, a5, 10-05-2023, 7d 
    Pandas                      :done, after a5, 7d
    PowerBI (not started)       :milestone, 02-05-2023, 0d
    PowerApps (not started)     :milestone, 0d
```

Basically, I set aside the days when I have more time to study C and Python, which are the biggest demands. Then comes SQL (Postgre and PostGis) along with PowerBI and PowerApps, for application in the company.

About the time, if you manage to reconcile between demands intervals, great, if not... Use the reserved time per day.

## First time with Markdown?
> Enter [here](./src/first-time.md)

## Some useful [links](links.md) 