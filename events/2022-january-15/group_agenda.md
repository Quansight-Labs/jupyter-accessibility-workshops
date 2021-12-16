#  Jupyter Accessibility Workshops with Frank Elvasky: How to build inclusive data representations

## Event details

Date: January 15, 2022

Overview: A friendly virtual event that brings Jupyter and PyData community members together to learn from an accessibility expert. 

## Takeaways

Jupyter and PyData members will leave better informed and more empathetic to accessibility considerations in their work while the accessibility community will become familiar with Jupyter and its open-source challenges.

## What you need to participate

* Some familiarity with data/visualization skills

## Schedule

```mermaid
gantt

    dateFormat YYYY-MM-DD hh:mm
    axisFormat  %H:%M

    section icebreaker
    meet and greet :meet, 2021-10-02 08:45, 15min
    welcome, welcome, welcome :welcome, after meet, 15min
        
    section introductions
    intro to jupyter :jupyter, after welcome, 10min 
    jupyterlab accessibility :ja11y, after jupyter, 10min
    ally 101 :a101y, after ja11y, 15min
        
    section main 
    main speaker :main, after a101y, 35min
    questions :qa, after main, 25min
    
    
    section breakouts
    breakout topics :topics, after qa, 5min
    break :break, after topics, 5min
    breakout 1 :b1, after topics, 30min
    breakout 2 :b2, after topics, 30min
    summarize :regroup, after b1, 10min
    breakout 1 :b21, after regroup, 25min
    breakout 2 :b22, after regroup, 25min
        
    section conclusion
    final comments :end, after b21, 15min
    
    section hangout (optional)
    hangout :hang, after end, 45min
    
    
```    

* Enter in breakout rooms (like you're about to go on an amusement park ride)
* Welcome and set goals
    * To educate and introduce the Jupyter community to accessibility concerns 
    in software.
    * Connect the Jupyter community to accessibility experts and disabled 
    people.
    * Learn about web content accessibility through expert content and group 
    discussions.
* Intro to Jupyter and Jupyterlab accessibility
    * JupyterLab's accessibility now is a work in progress (includes efforts 
    on skip links, tab index, modal focus, contrast)
    * Goals: WCAG as a baseline with looking for more feedback on specific 
    Jupyter needs, manual and automated testing, best practices for sharing 
    cross-project
    * Where to join the community now (repository, meetings)
* Main speaker
    * Frank Elavsky of [Chartability](https://chartability.fizz.studio/) on how to build inclusive data representations
* Break
* Discussion breakout rooms
    * This is a chance for attendees to reflect on what they've learned and share their own knowledge/
* Wrap up
    * Upcoming events
    * How to stay up-to-date with accessibility efforts in Jupyter
    * Please fill out the feedback survey so we make sure these events are helpful and fun for the community!
* Hangout/cooldown (optional)

## Further reading

Resources for people interested in learning more about accessibility outside 
the event.

* [Chartability](https://chartability.fizz.studio/)
* [Not so short note on aria-label usage](https://html5accessibility.com/stuff/2020/11/07/not-so-short-note-on-aria-label-usage-big-table-edition/)
* [Resources For Building Accessible Tables](https://www.digitala11y.com/resources-for-building-accessible-tables/)
* [pydata-sphinx-theme #294 Add pa11y testing and reporting](https://github.com/pydata/pydata-sphinx-theme/pull/294#issuecomment-907404315)
* [ 18F Accessibility Guide Checklist](https://accessibility.18f.gov/checklist/)
* [Maintainers Summit at PyCon US 2021 - Building Accessibility into Open Source Projects: Thibaud Colas](https://youtu.be/9XI-8ZvU2w0)
* [Accessible icon links](https://kittygiraudel.com/2020/12/10/accessible-icon-links/)
* [A guide to designing accessible, WCAG-compliant focus indicators ](https://www.sarasoueidan.com/blog/focus-indicators/)