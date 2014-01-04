imsakiyah.sh
============

Very simple bash script to display praying time (Sholat). Made for my conky.

####HOWTO?
   *  Give permission and run
      1. `$ chmod +x imsakiyah.sh`
      2. `$ ./imsakiyah.sh`

Output
   * `Sb 03:52 ~ Tb 05:14 ~ Dh 11:35 ~ As 15:02 ~ Mg 17:53 ~ Is 19:09`

####NOTICE
   All praying time are set to Malang, East Jawa, Indonesia local time.
   You can get your local praying time here: [http://www.jadwalsholat.org/adzan/monthly.php?id=141](http://www.jadwalsholat.org/adzan/monthly.php?id=141) (**Indonesia Only**) and then paste it to this script yourself.

Because this script does is only read its contents itself and then displays the corresponding praying times by comparing the combination of the date and month in each row, you might have to format your local praying times to match the example provided in this script. Like this:

```bash
# 0101 Sb 03:51 ~ Tb 05:13 ~ Dh 11:34 ~ As 15:01 ~ Mg 17:52 ~ Is 19:08
# 0201 Sb 03:51 ~ Tb 05:13 ~ Dh 11:35 ~ As 15:01 ~ Mg 17:52 ~ Is 19:09
# 0301 Sb 03:52 ~ Tb 05:14 ~ Dh 11:35 ~ As 15:02 ~ Mg 17:52 ~ Is 19:09
```

Those lines are praying times for January 1st - 3st, if you want to change to your local time, then it should be like this:

```bash
# 0101 [your local praying time]
# 0201 [your local praying time]
# 0301 [your local praying time]
```

Or `# ddmm[space][your local praying time]`
