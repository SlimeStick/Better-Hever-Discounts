Hever card loader is a project to automate utilizing the loading mechanism specified in Hever's EULA in order to get higher discount percentages when loading your Hever card.

Using it during regular months should increase your discount by up to 5% (if before you were loading at 28% and now you load at 33%)

In order to run the script you should install python3 the pyautogui package.

Running the script:
python hever_discount_script.py --load-count 4 --card-type food --current-discount-percentage 0.3 --card-number 5555555555554444 --year 2030 --month 03 --cvv 737

Note that you should not load your cards more than 5 times as Hever's EULA says your card will get frozen for 24 hours if you do so.
