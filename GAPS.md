# What this repository does not hold — 110th Congress

314 measures are recorded in BILLSTATUS but have no bill text
linked in any of their `textVersions` entries, so they have no branch in
this repository.

This is an upstream gap, not a build failure. It is heavily
concentrated in the older Congresses: govinfo's coverage of bill text
thins out before the 111th, and House organizing resolutions -- electing
officers, adopting rules -- generally carry no published text in any
Congress.

## By measure type

| Type | Without text |
|---|---|
| `s` | 144 |
| `hr` | 120 |
| `hres` | 27 |
| `sres` | 11 |
| `hconres` | 7 |
| `hjres` | 2 |
| `sjres` | 2 |
| `sconres` | 1 |

## The first 50

The complete list of 314 is in [`GAPS.tsv`](GAPS.tsv), which
is tab-separated so it can be grepped and diffed without a Markdown
reader.

| Measure | Title |
|---|---|
| `H.Con.Res. 6` | Expressing the sense of Congress that the Supreme Court misinterpreted the First Amendment to the Constitution in the case of Buckley v. Valeo. |
| `H.Con.Res. 26` | Expressing the sense of the Congress that the United States Postal Service should issue a postage stamp commemorating Congressman Adam Clayton Powell, Jr. |
| `H.Con.Res. 48` | Recognizing the efforts and contributions of the members of the Monuments, Fine Arts, and Archives program under the Civil Affairs and Military Government Sections of the United States Armed Forces during and following World War II who were responsible for the preservation, protection, and restitution of artistic and cultural treasures in countries occupied by the Allied armies. |
| `H.Con.Res. 270` | To make corrections in the enrollment of the bill H.R. 1593. |
| `H.Con.Res. 271` | Providing for the sine die adjournment of the first session of the One Hundred Tenth Congress. |
| `H.Con.Res. 312` | Revising the congressional budget for the United States Government for fiscal year 2008, establishing the congressional budget for the United States Government for fiscal year 2009, and setting forth appropriate budgetary levels for fiscal years 2010 through 2013. |
| `H.Con.Res. 338` | Recognizing the Honorable Yvonne Brathwaite Burke for her distinguished career in public service. |
| `H.J.Res. 4` | Every Vote Counts Amendment |
| `H.J.Res. 38` | Proposing an amendment to the Constitution of the United States to authorize the line item veto. |
| `H.R. 15` | National Health Insurance Act |
| `H.R. 25` | Fair Tax Act of 2007 |
| `H.R. 48` | To redesignate the White Rocks National Recreation Area in the State of Vermont as the "Robert T. Stafford White Rocks National Recreation Area". |
| `H.R. 76` | To amend the Internal Revenue Code of 1986 to increase the number vehicles for which the alternative motor vehicle credit is allowed. |
| `H.R. 89` | Combat-Related Special Compensation Act |
| `H.R. 96` | Gun Show Loophole Closing Act of 2007 |
| `H.R. 97` | Accountability and Transparency in Ethics Act |
| `H.R. 98` | Illegal Immigration Enforcement and Social Security Protection Act of 2007 |
| `H.R. 121` | High-Performance Green Buildings Act of 2007 |
| `H.R. 129` | To direct the Director of the Federal Emergency Management Agency to designate New Jersey Task Force 1 as part of the National Urban Search and Rescue System. |
| `H.R. 173` | One Strike and You're Out! Act of 2007 |
| `H.R. 250` | National Oceanic and Atmospheric Administration Act |
| `H.R. 352` | Poverty Impact Trigger Act of 2007 |
| `H.R. 422` | To establish the Office of Public Integrity as an independent office within the legislative branch of the Government, to reduce the duties of the Committee on Standards of Official Conduct of the House of Representatives and the Select Committee on Ethics of the Senate, and for other purposes. |
| `H.R. 563` | Congressional Pardon for Border Patrol Agents Ramos and Compean Act |
| `H.R. 631` | Earmark Transparency and Accountability Act of 2007 |
| `H.R. 648` | No Child Left Behind Improvements Act of 2007 |
| `H.R. 708` | Trade Law Reform Act of 2007 |
| `H.R. 775` | Supplemental Appropriations Act for Defense and for the Reconstruction of Iraq, 2007 |
| `H.R. 1013` | To amend title XXI of the Social Security Act to prohibit the approval or continuation of section 1115 waivers insofar as they provide coverage of nonpregnant adults under the State Children's Health Insurance Program (SCHIP). |
| `H.R. 1136` | Ethics Reform Act of 2007 |
| `H.R. 1159` | To amend title II of the Social Security Act to provide for full benefits for disabled widows and widowers without regard to age. |
| `H.R. 1161` | Social Security Caregiver Credit Act of 2007 |
| `H.R. 1207` | To amend the Internal Revenue Code of 1986 to impose an excise tax on any tax-exempt organization which accepts any contribution which may be used to relocate property held by the organization if the relocation is contrary to the intent of the donor of the property. |
| `H.R. 1356` | Next Generation Air Transportation System Financing Reform Act of 2007 |
| `H.R. 1375` | Earmark Accountability and Reform Act of 2007 |
| `H.R. 1591` | U.S. Troop Readiness, Veterans' Care, Katrina Recovery, and Iraq Accountability Appropriations Act, 2007 |
| `H.R. 1600` | EAT Healthy America Act |
| `H.R. 1637` | For the relief of Malachy McAllister, Nicola McAllister, and Sean Ryan McAllister. |
| `H.R. 1647` | To amend title XIX of the Social Security Act to include podiatrists as physicians for purposes of covering physicians services under the Medicaid Program. |
| `H.R. 1672` | To amend the Internal Revenue Code of 1986 to deny qualified dividend income treatment to certain foreign dividends. |
| `H.R. 1739` | National Security Letter Judicial and Congressional Oversight Act |
| `H.R. 1754` | House Ethics Commission Establishment Act of 2007 |
| `H.R. 1841` | AmeriCare Health Care Act of 2007 |
| `H.R. 1858` | District of Columbia-Maryland Reunion Act |
| `H.R. 1909` | Federal Criminal Immigration Courts Act of 2007 |
| `H.R. 1938` | Hunger-Free Communities Act of 2007 |
| `H.R. 1951` | Legal Employee Verification Act |
| `H.R. 1992` | Decent Working Conditions and Fair Competition Act |
| `H.R. 1994` | Financial Aid Accountability and Transparency Act of 2007 |
| `H.R. 2031` | To safely redeploy United States troops from Iraq. |

## Roll-call votes taken after the last published text

256 roll calls were taken later than the most recent
dated text version of their measure, so there is no commit for them to
sit on. Every record in this repository is the record *as of* the version
it accompanies -- see the caveat in the README -- and a vote cannot be
written onto text that predates it.

This is a limit of the shape of this repository, not an upstream gap and
not a build failure. The votes themselves are published; they are listed
here with the address the chamber serves them from.

The complete list of 256 is in [`GAPS-late-votes.tsv`](GAPS-late-votes.tsv),
which is tab-separated so it can be grepped and diffed without a
Markdown reader. The first few:

| Measure | Vote | When |
|---|---|---|
| `hconres-398` | Senate 110-2-196 | 2008-07-31, after the last version committed (2008-07-30) |
| `hr-2` | Senate 110-1-20 | 2007-01-23, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-21 | 2007-01-23, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-22 | 2007-01-24, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-23 | 2007-01-24, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-24 | 2007-01-24, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-25 | 2007-01-25, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-26 | 2007-01-25, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-27 | 2007-01-25, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-28 | 2007-01-25, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-29 | 2007-01-25, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-30 | 2007-01-25, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-31 | 2007-01-25, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-32 | 2007-01-25, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-34 | 2007-01-30, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-37 | 2007-01-31, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-38 | 2007-01-31, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-39 | 2007-01-31, after the last version committed (2007-01-11) |
| `hr-2` | Senate 110-1-42 | 2007-02-01, after the last version committed (2007-01-11) |
| `hr-6` | House 110-1-1177 | 2007-12-18, after the last version committed (2007-12-07) |
| `hr-6` | Senate 110-1-425 | 2007-12-13, after the last version committed (2007-12-07) |
| `hr-6` | Senate 110-1-430 | 2007-12-13, after the last version committed (2007-12-07) |
| `hr-327` | House 110-1-987 | 2007-10-23, after the last version committed (2007-03-22) |
| `hr-556` | House 110-1-614 | 2007-07-11, after the last version committed (2007-03-01) |
| `hr-800` | Senate 110-1-227 | 2007-06-26, after the last version committed (2007-03-02) |
| `hr-980` | Senate 110-2-126 | 2008-05-13, after the last version committed (2007-07-20) |
| `hr-980` | Senate 110-2-127 | 2008-05-14, after the last version committed (2007-07-20) |
| `hr-1585` | House 110-1-1127 | 2007-12-05, after the last version committed (2007-06-05) |
| `hr-1585` | House 110-1-1128 | 2007-12-05, after the last version committed (2007-06-05) |
| `hr-1585` | House 110-1-1151 | 2007-12-12, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-241 | 2007-07-11, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-242 | 2007-07-11, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-243 | 2007-07-11, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-244 | 2007-07-11, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-245 | 2007-07-12, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-246 | 2007-07-12, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-247 | 2007-07-13, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-248 | 2007-07-17, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-252 | 2007-07-18, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-340 | 2007-09-19, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-341 | 2007-09-19, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-342 | 2007-09-19, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-343 | 2007-09-20, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-344 | 2007-09-20, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-345 | 2007-09-20, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-346 | 2007-09-21, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-348 | 2007-09-26, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-349 | 2007-09-26, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-350 | 2007-09-27, after the last version committed (2007-06-05) |
| `hr-1585` | Senate 110-1-351 | 2007-09-27, after the last version committed (2007-06-05) |

## What the derived amendment execution could not do

104,728 amendatory instructions were read from the measures in this
repository, and **14,181 of them (13.5%) were
carried out**. Each measure's `derived/amendments.md` holds its own,
with the reason beside every one that was not.

This is not a build failure and it is not going to improve much. A bill
is a list of instructions *about* law, and most of them refer to the law
by structure — *strike subsection (k)* — so the words being removed are
in the US Code and not in the bill. Nothing here guesses them. An
instruction is carried out only where the bill states both the text
removed and the text inserted, so the result follows from the bill alone
and can be checked against it.

| Why an instruction was not carried out | Instructions |
|---|---|
| the bill names no machine-readable US Code section | 52,958 |
| the instruction refers to the law by structure rather than quoting it, so the words it changes are in the US Code and not in this bill | 26,242 |
| the bill quotes the text inserted but describes where it goes | 6,424 |
| the bill quotes the text struck but describes what replaces it | 4,789 |
| the bill quotes text on both sides, but not as a single substitution this could carry out | 134 |

**The rate varies enormously between Congresses, and that is upstream.**
An instruction can only be placed if GPO tagged the citation it names,
and whether they did is a fact about the year rather than about the
bill: sampled at 1,500 documents per Congress, 64% of the 108th's carry
a machine-readable US Code citation, 55% of the 113th's — and 5% of the
111th's and 5% of the 112th's. So a Congress here may report a very low
share carried out while the reading of it worked perfectly. Compare this
table with a neighbouring Congress before concluding anything about the
bills themselves.

Counted on each measure's last committed version. An instruction
usually survives from the introduced text to the enrolled one, so
counting every version would report the same instruction several times.
