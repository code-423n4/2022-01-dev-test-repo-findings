---
sponsor: "Purple Cow"
slug: "2022-01-dev-test-repo"
date: "YYYY-MM-DD"  # the date this report is published to the C4 website
title: "Sample, eh? — finished copy"
findings: "https://github.com/code-423n4/2022-01-dev-test-repo-findings/issues"
contest: 101
---

# Overview TEST

## About C4

Code4rena (C4) is an open organization consisting of security researchers, auditors, developers, and individuals with domain expertise in smart contracts.

A C4 audit is an event in which community participants, referred to as Wardens, review, audit, or analyze smart contract logic in exchange for a bounty provided by sponsoring projects.

<!-- ⭕  contest start/end dates can be found at https://code4rena.com/contests -->
During the audit outlined in this document, C4 conducted an analysis of the Sample, eh? — finished copy smart contract system written in . The audit took place between January 1—December 15 2023.

## Wardens

<!-- ⭕  This counts teams as individuals; for each team, add 1 less than the number of members -->
5 Wardens contributed reports to the Sample, eh? — finished copy:

  1. [say-cheese](https://code4rena.com/@say-cheese)
  2. [kartoonjoy](https://code4rena.com/@kartoonjoy)
  3. [Go Team](https://code4rena.com/@Go Team) ([0xk4w4ida](https://code4rena.com/@0xk4w4ida),[bluejacket](https://code4rena.com/@bluejacket),[say-cheese](https://code4rena.com/@say-cheese))
  4. [0xk4w4ida](https://code4rena.com/@0xk4w4ida)
  5. [nighthawk](https://code4rena.com/@nighthawk)

<!-- ⭕
  Judge information can be found on the Notion Contests kanban board
  https://www.notion.so/code4rena/718dee359e0a4cf89cfe58d48beeb9e9?v=3c2cf0ba5265435ead2ef55f391795af

  Twitter handles can be found on the Notion Judges page
  https://www.notion.so/code4rena/249fa3c05f934dea8c1b8ce1f0f9c942?v=d59575cc87e246fea6ab84e9c0ed4b3c
-->
This audit was judged by [JUDGE](https://twitter.com/judge).

Final report assembled by [liveactionllama](https://twitter.com/liveactionllama).

# Summary

The C4 analysis yielded an aggregated total of 2 unique vulnerabilities. Of these vulnerabilities, 0 received a risk rating in the category of HIGH severity and 2 received a risk rating in the category of MEDIUM severity.

Additionally, C4 analysis included 1 reports detailing issues with a risk rating of LOW severity or non-critical. There were also 1 reports recommending gas optimizations.

All of the issues presented here are linked back to their original finding.

# Scope

<!-- ⭕  count the .sol files in the audit contest repository -->
The code under review can be found within the [C4 Sample, eh? — finished copy repository](https://github.com/code-423n4/2023-01-sample-data-a), and is composed of 0 smart contracts written in the Solidity programming language and includes 0 lines of Solidity code.

# Severity Criteria

C4 assesses the severity of disclosed vulnerabilities based on three primary risk categories: high, medium, and low/non-critical.

High-level considerations for vulnerabilities span the following key areas when conducting assessments:

- Malicious Input Handling
- Escalation of privileges
- Arithmetic
- Gas use

For more information regarding the severity criteria referenced throughout the submission review process, please refer to the documentation provided on [the C4 website](https://code4rena.com), specifically our section on [Severity Categorization](https://docs.code4rena.com/awarding/judging-criteria/severity-categorization).

# High Risk Findings (1)
## [[H-14] Upgraded G -> H from 9 [1653551814988]](https://github.com/code-423n4/2022-01-dev-test-repo-findings/issues/14)
*Submitted by [Go Team](https://github.com/code-423n4/2022-01-dev-test-repo-findings/issues/14)*

Judge has assessed an item in Issue #9 as H risk. The relevant finding follows:

**[c4-judge commented](https://github.com/code-423n4/2022-01-dev-test-repo-findings/issues/14#issuecomment-1398813191):**
 > captainmangoC4 marked the issue as duplicate of #91


**[c4-judge commented](https://github.com/code-423n4/2022-01-dev-test-repo-findings/issues/14#issuecomment-1398820436):**
 > captainmangoC4 marked the issue as partial-50


**[c4-judge commented](https://github.com/code-423n4/2022-01-dev-test-repo-findings/issues/14#issuecomment-1398837530):**
 > captainmangoC4 changed the severity to 2 (Med Risk)


**[c4-sponsor commented](https://github.com/code-423n4/2022-01-dev-test-repo-findings/issues/14#issuecomment-1664729382):**
 > captainmangoC4 marked the issue as sponsor disputed

***


# Gas Optimizations

For this audit, 1 reports were submitted by wardens detailing gas optimizations. The [report highlighted below](https://github.com/code-423n4/2022-01-dev-test-repo-findings/issues/9) by **nighthawk** received the top score from the judge.

*The following wardens also submitted reports: , and undefined.*

Testing gas

# test

- test
- test

## test
test

**[c4-sponsor commented](https://github.com/code-423n4/2022-01-dev-test-repo-findings/issues/9#issuecomment-1664723211):**
 > captainmangoC4 marked the issue as sponsor confirmed


***




# Disclosures

C4 is an open organization governed by participants in the community.

C4 audits incentivize the discovery of exploits, vulnerabilities, and bugs in smart contracts. Security researchers are rewarded at an increasing rate for finding higher-risk issues. Audit submissions are judged by a knowledgeable security researcher and solidity developer and disclosed to sponsoring developers. C4 does not conduct formal verification regarding the provided code but instead provides final verification.

C4 does not provide any guarantee or warranty regarding the security of this project. All smart contract software should be used at the sole risk and responsibility of users.
