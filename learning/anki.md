# anki

Anki is *mainly* a tool for memorization (*and later, understanding*), not first-pass learning. 

## Decks

Input all cards into one deck with hierarchical tags (**Class**). Use two other decks for current sections and overall reviews (**Combined Current** and **Combined Review** respectively).

After a unit/exam, move all cards from **Class** and **Combined Current** into **Combined Review**. Having one review deck promotes interleaved practice while allowing you to prioritize current sections. 

## Options

* Tools
    - Preferences
        + Basic
            * Show new cards after reviews

* **Class**
    - New Cards
        + Steps (in minutes): 15 90 1440 4320
        + Order: Show new cards in random order
        + New cards/day: X (default: 50)
        + Graduating interval
            * Minimum: 6 day
            * Maximum: 7 day
        + Easy interval
            * Minimum: 10 days
            * Maximum: 11 days
        + Starting ease: 250%
        + Bury related reviews until the next day: Unchecked        
    - Reviews
        + Maximum reviews/day: 9999
        + Easy bonus: 120%
        + Interval modifier: 70%
        + Maximum interval: 90 days
        + Bury related reviews until the next day: Unchecked
    - Lapses
        + Steps (in minutes): 20 60
        + New interval: 70%
        + Minimum interval: 2 day
        + Leech threshold: 8 lapses
        + Leech action: Tag Only

* **Combined Current** (inherits everything from "Class" except:)
    - New Cards
        + New cards/day: X (default: 50)

* **Combined Review** (inherits everything from "Class" except:)
    - New Cards
        + Steps (in minutes): 15 1440 4320
        + New cards/day: 9999
        + Graduating interval
            * Minimum: 14 day
            * Maximum: 15 day
        + Easy interval
            * Minimum: 60 days
            * Maximum: 61 days     
    - Reviews
        + Interval modifier: 100%
        + Maximum interval: 36500 days

X = number of cards to do/number of days until exam


## Add-ons

* [Advanced Previewer](https://ankiweb.net/shared/info/544521385)
* [Advanced Browser](https://ankiweb.net/shared/info/874215009)
* [Cloze Overlapper](https://ankiweb.net/shared/info/969733775)
* [Convert Subdecks to Tag Hierarchy](https://ankiweb.net/shared/info/1172858842)
* [Frozen Fields](https://ankiweb.net/shared/info/516643804)
* [Hierarchical Tags](https://ankiweb.net/shared/info/1089921461)
* [Image Occlusion Enhanced](https://ankiweb.net/shared/info/1111933094)
* [Load Balancer](https://ankiweb.net/shared/info/1417170896)
* [Night Mode](https://ankiweb.net/shared/info/1496166067)
* [Popup Dictionary](https://github.com/glutanimate/popup-dictionary)
* [Power Format Pack](https://ankiweb.net/shared/info/162313389)
* [Progress Bar](https://ankiweb.net/shared/info/2091361802)
* [Replay Buttons on Card](https://ankiweb.net/shared/info/498789867)
* [Review Heatmap](https://ankiweb.net/shared/info/1771074083)
* [Search and Replace Tags](https://ankiweb.net/shared/info/1771074083)
* [Sticky Searches](https://ankiweb.net/shared/info/594622823)
* [True Retention by Card Maturity](https://ankiweb.net/shared/info/923360400)
* [Zoom](https://ankiweb.net/shared/info/1956318463)

## [20 Rules](https://www.supermemo.com/en/articles/20rules)

1. Do not learn if you do not understand
2. Learn before you memorize
3. Build upon the basics
4. Stick to the minimum information principle
5. Cloze deletion is easy and effective
6. Use imagery
7. Use mnemonic techniques
8. Graphic deletion is as good as cloze deletion
9. Avoid sets
10. Avoid enumerations
11. Combat interference
12. Optimize wording
13. Refer to other memories
14. Personalize and provide examples
15. Rely on emotional states
16. Context cues simplify wording
17. Redundancy does not contradict minimum information principle
18. Provide sources
19. Provide date stamping
20. Prioritize

## Links

* [Anki 2.1 User Manual](https://apps.ankiweb.net/docs/manual.html)
* [Effective learning: Twenty rules of formulating knowledge](https://www.supermemo.com/en/articles/20rules)
* [Augmenting Long-term Memory](http://augmentingcognition.com/ltm.html)
* [Spaced-repetition](https://www.gwern.net/Spaced-repetition)
* [Shamim's Guide to Medical School Using Anki (USMLE Step 1 and Class)](https://medshamim.com/med/anki-step-one)
* [Guide to Anki Intervals and Learning Steps](https://www.youtube.com/watch?v=1XaJjbCSXT0)