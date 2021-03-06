Release Notes for TYPO3 4.6.14
==============================

This document contains information about TYPO3 version 4.6.14 which was
released on November 8th 2012.

News
----

This release is a combined bug fix and security release.

Notes
-----

Due to security issues found in the TYPO3 Core, there was a combined
release of TYPO3 4.5.21, 4.6.14 and 4.7.6.\
Find more details in the security bulletin:
<https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2012-005/>

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    ccd21858d4a2ebf551994b611ab0b98d  blankpackage-4.6.14.tar.gz
    98bceced82474f4dfca774c4774ebec4  blankpackage-4.6.14.zip
    1855cf707c51b669cd3f509bccb9bb63  dummy-4.6.14.tar.gz
    62753128fd6e4fbc3904a66dc33a2e0c  dummy-4.6.14.zip
    8f8a93dc53a0b58ca1ba9b74958f292a  typo3_src+dummy-4.6.14.zip
    aa629a826bbb251137fdbbd392bfc773  typo3_src-4.6.14.tar.gz
    f8fdc2b797732774643fd0a0497fd342  typo3_src-4.6.14.zip

Upgrading
---------

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.

Changes
-------

Here is a list of what was fixed since
[4.6.13](TYPO3_4.6.13 "wikilink"):

    2012-11-08  948f241                  [RELEASE] Release of TYPO3 4.6.14 (TYPO3 Release Team)
    2012-11-08  c150b27  #42696          [SECURITY] Fix SQL injection and XSS in record history (Oliver Hader)
    2012-11-08  b02026d  #42774          [SECURITY] XSS in TCA Tree (Oliver Hader)
    2012-11-08  f22dc79  #42776          [SECURITY] Fix potential XSS in t3lib_BEfunc::getFuncCheck (Helmut Hummel)
    2012-11-08  72153cc                  [TASK] Raise submodule pointer (TYPO3 Release Team)
    2012-11-07  3ea5e0b  #39677          [BUGFIX] No sorting in TypoScript Object Browser when browsing (Nicole Cordes)
    2012-11-02  5de1807  #42281          [BUGFIX] Translated non-published page in workspace breaks live workspace (Oliver Hader)
    2012-11-02  93bb671  #38024          [BUGFIX] Illegal string offsets in t3lib_stdgraphic (Wouter Wolters)
    2012-11-01  84cb9b6  #37578          [BUGFIX] PHP 5.4 warning in CLI context in switch back user (Christian Kuhn)
    2012-10-29  76d0b9c  #28248          [BUGFIX] t3lib_div: adjust substUrlsInPlainText to also work on URLs at end of sentence (Robert Heel)
    2012-10-29  3ff27f4  #40733          [BUGFIX] Wrong call to TSFE in FrontendEditing (Steffen Ritter)
    2012-10-29  9767b86  #42054          [BUGFIX] PHP warning: open_basedir restriction (Xavier Perseguers)
    2012-10-27  7381250  #42444          [TASK] Fix generation of ext_emconf.php (Wouter Wolters)
    2012-10-22  ccebb50  #38699          [BUGFIX] t3lib_div::unlink_tempfile does not always work on Windows (Stanislas Rolland)
    2012-10-22  2a0929b  #33504          [BUGFIX] New form wizard not loading in IE8 (Sebastian Schawohl)
    2012-10-19  b32e08c                  [BUGFIX] Fix case of tests folder (Xavier Perseguers)
    2012-10-19  22bef48                  [BUGFIX] Unit test for saltedpasswords fail (Xavier Perseguers)
    2012-10-18  9ed2c6f  #36087          [BUGFIX] RTE: Link to disabled page doesn't show in FE, link icon does (Stanislas Rolland)
    2012-10-18  2e48486  #29685          [BUGFIX] RTE: Words containing umlauts not added to personal dictionary (Stanislas Rolland)
    2012-10-17  a3a7417  #38406          [BUGFIX] Extension Import not working with postgresql and DBAL (Ernesto Baschny)
    2012-10-17  a5fc128  #25021          [BUGFIX] Creating new pages via drag'n'drop respects page TS (Philipp Kitzberger)
    2012-10-16  528c8bc                  [TASK] Set TYPO3 version to 4.6.14-dev (TYPO3 Release Team)
    2012-10-16  2c03804                  [RELEASE] Release of TYPO3 4.6.13 (TYPO3 Release Team)


