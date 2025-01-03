Software reliability data
-------------------------

The aim of this repository is to collect all the publicly available software reliability data having the form: "_fault_number,CPU_time_". Some exceptions have been made for reliability datasets used by multiple papers that analyse this kind of data.

Software reliability data is scattered over many papers, which can be hard to find.  For an analysis of this kind of data, download the Reliability chapter of the book [Evidence-Based Software Engineering](http://knosof.co.uk/ESEUR/)

If you know of any datasets that are missing, and you have the data, please send me a copy. Also, if you spot any mistakes, please let me know.

I have yet to find a copy of the widely cited paper: "Software Reliability Data" by J. D. Musa, 1979, Data and Analysis Center for Software, Rome Air Development Center, Rome, New York. It appears to contain datasets that are not present here.

Entries are listed in order of first author of the paper that first published the data.  Note that it's common for paper _X_ to cite _Y_ as the source of the data, without checking to find that _Y_ cites _Z_ as the source of the data (occasionally the citation chain is longer).

There are no commonly used naming conventions for this data.  It's common for authors to name the datasets they analyse as _DS1_, _DS2_, etc.  I have kept the names used when they make sense, otherwise I have used the convention _author_table_number_.

**anna_D11.csv**
S. Anna-Mary, "A Study of the MUSA reliability model," M.S. thesis, Dept. Comput. Sci., Univ. Maryland, College Park, MD, USA 1980, data from [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

118 rows

The software system is a flight dynamic application consisting of 10,000 lines of code.  The cumulative test time is reported in hours.

**anna_D12.csv**
S. Anna-Mary, "A Study of the MUSA reliability model," M.S. thesis, Dept. Comput. Sci., Univ. Maryland, College Park, MD, USA 1980, data from [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

180 rows

The software system is a flight dynamic application consisting of 22,500 lines of code.  The cumulative test time is reported in hours.

**anna_D13.csv**
S. Anna-Mary, "A Study of the MUSA reliability model," M.S. thesis, Dept. Comput. Sci., Univ. Maryland, College Park, MD, USA 1980, data from [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

213 rows

The software system is a dynamic application consisting of 38,500 lines of code.  The cumulative test time is reported in hours.

**Brooks_p1.csv**
Brooks W. D., R.W. Motley, "Analysis of Discrete Software Reliability Models," RADC-TR-80-84, Apr 1980, Rome Air Development Center.  Table 3.2.2-1.

12 rows

Formal testing of large command and control software written in CENTRAN and Assembly Language.

**Brooks_p2.csv**
Brooks W. D., and Motley R. W., "Analysis of Discrete Software Reliability Models," RADC-TR-80-84, Apr 1980, Rome Air Development Center.  Table 3.2.2-2.

35 rows

Formal testing of 317 KLOC of Jovial for a real-time command and control system.

**BAe.csv**

Chan P. Y.,  "Software reliability prediction" Doctoral thesis, 1986, The City University, London.

207 rows

Assumed to be some unknown time interval between faults.  From British Aerospace.

**ODC1.csv**
Chillarege R., "Orthogonal Defect Classification", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

1207 rows

This data set is taken from a large IBM project with several tens of thousands of lines of code.  This data set has 1207 data entries.  Each data entry represents a detected defect during the development phase.

- Column 1 - Date (Sequential Day)
- Column 2 - Defect Type, including:
  -    "Ck" means checking
  -    "alg" means algorithm
  -    "Misc" means Miscellaneous
  -    etc.

**ODC2.csv**
Chillarege R., "Orthogonal Defect Classification", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

255 rows

This data set is taken from the high-level design inspection of an IBM middleware project.  This data set has 255 entries.  The data entries dated in 1991 (entries 1-86 and 189-255 for 153 records) are the defects detected in the initial inspection, while the data entries dated in 1992 (entries 87-188 for 102 records) are the defects found in the additional review.

**ODC3.csv**
Chillarege R., "Orthogonal Defect Classification", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

400 rows

**ODC4.csv**
Chillarege R., "Orthogonal Defect Classification", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

208 rows

**ODC5.csv**
Chillarege R., "Orthogonal Defect Classification", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

378 rows

**ODC6.csv**
Chillarege R., "Orthogonal Defect Classification", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

196 rows

**dalal_tI.csv**
Dalal S. R. and McIntosh A. A.,"When to Stop Testing for Large Software Systems with Changing Code," IEEE Transactions on Software Engineering, vol 20(4) Apr 1994, pages 318-323.

198 rows

System A is a large telecommunications software system, consisting of approximately 7,000,000 noncommentary source lines (NCSL).  The data is for the subsequent 400,000 new or changed noncommentary source lines (NCNCSL) which added new features or fixed existing faults.

**goel_tII.csv**
Goel A. L., "Software Reliability Models: Assumptions, Limitations, and Applicability", Transactions on Software Engineering, vol. SE-11, NO. 12, Dec 1985, pages 1411-1423.  The cited source is Musa's "Software Reliability Data," DACS report.

25 rows

A system containing 21,700 object instructions developed by Bell Laboratories.

**NTDS.csv**
Goel A. L., and Okumoto K., "Time-Dependent Error-Detection Rate Model for Software Reliability and Other Performance Measures", IEEE Transactions on Reliability, Vol. R-28(3), Aug 1979.  The cited source is: Jelinski Z., and Moranda P., “Software reliability research”, in "Statistical Computer Performance Evaluation", ed Freiberger W., Academic Press, 1972, pp 465-484, which does not actually contain the data.

34 rows

The data from the U.S. Navy Fleet Computer Programming Center, and consist of the errors in the development of software for the real-time, multicomputer complex. The NTDS software consisted of some 38 different modules. Each module was supposed to follow three stages: production (development) phase, test phase, and user phase. The data are based on the trouble reports or ‘software anomaly reports’ for one of the larger modules, denoted as A-module ans gives the times (days) between software failures. Twenty six software errors were found during production phase and five additional errors during test phase. The ‘last’ error was found on 4 Jan 1971. Then, one error was observed during the user phase on 20 Sep 1971, and two more errors (1971 Oct 5/10 Nov) during a subsequent test phase, indicating that a rework of the module had taken place after the user error was found.

**TABLE20.csv**
Iyer R. K., and I. Lee, "Measurement-Based Analysis of Software Reliability", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

186 rows

Processor failure data collected from a distributed system consisting of 5 processors connected by a local network.

The time unit is second and time 0 is 12am, 10/1/1987.  The measurement started from 12am, 12/9/1987 (29,548,800) and ended at 12am, 8/15/1988 (51,148,800), covering 250 days. The error type means the type of error that causes a processor failure.  Possible error types are CPU, I/O (network or disk problems), software, and unknown.

**DATASET1.csv**
Jones W. D., "Field Data Analysis", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

141 rows

Field data from a large release of a telecommunications switch software.

Date is calendar-time.

Format:

Cum Failures is the percentage of the total number of software failure experienced in the calendar interval reported in the table,
Cum Usage Time is the percentage of the total in-service time accumulated over the calendar interval reported, and
Sites is the percentage of sites that have this version of the software release loaded on a given date.

Note that the data set has been normalized to protect proprietary information.

**DATASET2.csv**
Jones W. D., "Field Data Analysis", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

111 rows

Data set contains 36 months of defect-discovery times for a release of Controller Software consisting of about 500,000 lines of code installed on over 100,000 controllers. The defects are those that were present in the code of the particular release of the software, and were discovered as a result of failures reported by users of that release, or possibly of the follow-on release of the product.

**DATASET3.csv**
See SS1.csv

**DATASET4.csv**
Jones W. D., "Field Data Analysis", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

32 rows

Cited source: "The KAT (knowledge-action-transformation) approach to the modeling and evaluation of reliability and availability growth," J.-C. Laprie K. Kanoun; C. Beounes, and M. Kaaniche.

Brazilian Electronic Switching System, TROPICO R-4096 for 4096 subscribers. Software size is about 300 kb written in Assembly Language.

**DATASET5.csv**
Jones W. D., "Field Data Analysis", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

14 rows

Cited source: "Practical Quantitative Methods of Improving Software Quality: Based on Decades of Experience,"  Onoma, A.K., and Yamaura, T, NRC Workshop on Statistics in Software Engineering, NRC, Washington, D.C., October 1993.

Hitachi Software tracks the number of system failures detected at customer sites. Filed Failure Ratio (FFR) is the number of system failures per month per thousand systems.

**DATASET6.csv**
Jones W. D., "Field Data Analysis", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

100 rows

Cited source: Pruett, W.R., Personal Communication and Data Clarification Report, NASA,January 26,1995.

*SSOF Software Severity Classification*

Classification approach is based on the following categories:
Severity, Problem visibility to users, Assessment description and Discriminators. The definitions and discriminators are intended to convey the intent of the severity assessment categories and to allow a realistic evaluation of the potential effect of a software error. The objective is to determine the potential impact of each error if it were to occur e during a "pre-design" flight scenario.  The following severity assessments apply to the Shuttle flight software as a subsystem and represent a different entity than the safety, reliability ,and quality assurance criticality rating for the entire shuttle system.

*SEVERITY: 1, 1N*
Problem visibility to users: Perceivable to user

Assessment description: Severe vehicle or crew performance effects possible - usually fixed on next flight (SEV 1N are usually waived/noted)

*Discriminators:*
SEV 1 - Regardless of the probability of occurrence of the code error during an ALLOWED "operational scenario", the code error can cause loss of control, explosion, or other hazardous effect.

SEV 1N - Established or reasonable procedures PRECLUDE any operational scenarios for which the error could become a failure. If unusual or unreasonable action is required to avoid failure, then the problem IS severity 1.
OR the number of hardware/software system failures required to execute the code error exceeds the design requirements for the software or system.

*SEVERITY: 2, 2N*
Problem visibility to users: Perceivable to user

Assessment description: Could affect ability to complete mission objectives - not a loss of vehicle or crew issue, usually fixed on next flight (SEV 2N are usually waived/noted)

Discriminators:
SEV 2 - Regardless of the probability of occurrence of the code error during an ALLOWED "operational scenario", the code error can cause an inability to achieve mission objectives such as: launch, mission duration, payload deployment, etc.

SEV 2N - Established or reasonable procedures PRECLUDE any operational scenarios for which the error could become a failure. If unusual or unreasonable action is required to avoid failure, then the problem IS  severity 2.
OR the number of failures required to execute the code error exceeds the design requirements for the software system.

*SEVERITY: 3*
Problem visibility to users: Perceivable to user, Not a safety or mission objectives issue

*Assessment description:*
No impact to safety or mission objectives - usually waived or OPS noted, includes failures that are very likely to occur, but are insignificant in result, have minimal effects on operations, or are easily controlled procedurally.

Discriminators:
The effects are perceivable to the user but are not severity 1 or 2.

*SEVERITY: 4*

Problem visibility to users: Not perceivable to user when executed.

Assessment description:
Insignificant violation of requirements - includes input/output and display errors not detectable by human senses, includes errors only detectable by special debug processes, usually waived without OPS notes.

Discriminators: Not perceivable to user when executed. of the software (Flight Operations, Training, Testing), subtle or insignificant code implementation issues which do not exactly match requirements.

*PROFILES*

Space Shuttle On-board Flight Software release profiles
(January 1, 1986 - December 1, 1994).

Variables -
_Release_: release code
_Date_: date of release mm/dd/yy
_Size_: the number of new or changed lines of code (in thousands of lines)

|Release| Date|  Size|
|:------|----:|-----:|
|REL-A| 9/14/82 | 584|
|REL-B| 11/23/82| 4|
|REL-C| 6/7/83  | 10.6|
|REL-D| 9/1/83  | 8|
|REL-E| 12/20/83| 11.4|
|REL-F| 6/8/84  | 5.9|
|REL-G| 10/5/84 | 12.2|
|REL-H| 2/15/85 | 8.8|
|REL-I| 12/17/85| 6.6|
|REL-J| 6/5/87  | 6.3|
|REL-K| 9/11/87 | 3.1|
|REL-L| 10/13/88| 7|
|REL-M| 6/29/89 | 12.1|
|REL-N| 10/13/89| 1.9|
|REL-O| 6/18/90 | 29.4|
|REL-P| 5/02/91 | 21.3|
|REL-Q| 6/11/92 | 34.4|
|REL-R| 7/15/93 | 24|
|REL-S| 7/13/94 | 10.4|
------------------------------

*FAILURES*

Space Shuttle On-board Flight Software failure data

(January 1, 1986 - December 1, 1994).

Variables -
_FID_: failure identification number
_Date_: date failure was observed mm/dd/yy
_Release_: release in which it was introduced (see above)
_Severity_: severity of the observed failure
_UsageMode_: Usage mode in which failure was observed
_ObservedIn_: release in which the failure was observed (releases A through R)

**S27.csv**
Kanoun K., and J-C. Laprie "Trend Analysis", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

41 rows

**S2a.csv**
Kanoun K., and J-C. Laprie "Trend Analysis", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

54 rows

Time in seconds.

**S2b.csv**
Kanoun K., and J-C. Laprie, "Trend Analysis", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

22 rows

Failures per 5,000 seconds interval.

**SS1.csv**
Kanoun K., M.R. de Bastos Martini; J.M. de Souza, "A method for software reliability analysis and prediction application to the TROPICO-R switching system," IEEE Transactions on Software Engineering Vol 17(4) pages 334-344, Apr 1991.

81 rows

Brazilian Electronic Switching System, TROPICO R-1500 for 1500 subscribers. Software size is about 300 kb written in Assembly Language. Entries 1 through 30 were obtained during system VALIDATION phase,  entries 31 through 42 during FIELD TRIALS, and entries 43 through 81 during system OPERATION.

**Matsumoto_t2.csv**
Matsumoto K., K. Inoue, T.Kikuno, and K. Torii, "Experimental Evaluation of Software Reliability Growth Models", 1988, The Eighteenth International Symposium on Fault-Tolerant Computing.

27 rows

Cumulative number of faults detected up to time t (minutes) in five student implementations of a compiler for a subset of Pascal (each around 1,000 lines).

**apollo8.csv**
Mazzuchi T. A., Soyer R., "A Bayes Empirical-Bayes Model for Software Reliability", IEEE Transactions on Reliability, vol. 37(2), pages 248-254, Jun 1988. The cited source is: Jelinski Z., and Moranda P., “Software reliability research”, in "Statistical Computer Performance Evaluation", ed Freiberger W., Academic Press, 1972, pp 465-484, which does not actually contain the data.

26 rows

Apollo 8 software test data.

**Stratus-1.csv**
Robert E. Mullen, R. E., "The Lognormal Distribution of Software Failure Rates: Application to Software Reliability Growth Modeling", Proceedings Ninth International Symposium on Software Reliability Engineering, pages 134-142, 1998.

73 rows

Several hundred years of customer exposure on an operating system release containing over one million lines of code, supporting fault tolerant hardware. Series lists the cumulative number of machine-hours and the cumulative number of distinct faults discovered on a weekly basis. Each machine was attached to the Stratus Remote Service Network (RSN); failures reported by customers are logged; if a call due to a fault a bug number is assigned to the call. If the fault has not been seen before, a new bug number is assigned. The earliest call for each fault (bug number) identifies the calendar week in which a failure due to the fault first occurred.

**Stratus-2.csv**
Robert E. Mullen, R. E., "The Lognormal Distribution of Software Failure Rates: Application to Software Reliability Growth Modeling", Proceedings Ninth International Symposium on Software Reliability Engineering, pages 134-142, 1998.

120 rows

Several hundred years of customer exposure on an operating system release containing over one million lines of code, supporting fault tolerant hardware. Series lists the cumulative number of machine-hours and the cumulative number of distinct faults discovered on a weekly basis. Each machine was attached to the Stratus Remote Service Network (RSN); failures reported by customers are logged; if a call due to a fault a bug number is assigned to the call. If the fault has not been seen before, a new bug number is assigned. The earliest call for each fault (bug number) identifies the calendar week in which a failure due to the fault first occurred.

**CSR1.csv**
Musa, J. D., "Software Reliability Data," Technical Report, Data and Analysis Center for Software, Rome Air Development Center, Griffins AFB, New York, 1979.  via [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

397 rows

**CSR2.csv**
Musa, J. D., "Software Reliability Data," Technical Report, Data and Analysis Center for Software, Rome Air Development Center, Griffins AFB, New York, 1979.  via [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

129 rows

**CSR3.csv**
Musa, J. D., "Software Reliability Data," Technical Report, Data and Analysis Center for Software, Rome Air Development Center, Griffins AFB, New York, 1979.  via [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

104 rows

**SS3.csv**
Musa, J. D., "Software Reliability Data," Technical Report, Data and Analysis Center for Software, Rome Air Development Center, Griffins AFB, New York, 1979.  via [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

278 rows

**SS4.csv**
Musa, J. D., "Software Reliability Data," Technical Report, Data and Analysis Center for Software, Rome Air Development Center, Griffins AFB, New York, 1979.  via [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

197 rows

**SYS1.csv**
Musa, J. D., "Software Reliability Data," Technical Report, Data and Analysis Center for Software, Rome Air Development Center, Griffins AFB, New York, 1979.  via [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

136 rows

**SYS2.csv**
Musa, J. D., "Software Reliability Data," Technical Report, Data and Analysis Center for Software, Rome Air Development Center, Griffins AFB, New York, 1979.  via [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

86 rows

**SYS3.csv**
Musa, J. D., "Software Reliability Data," Technical Report, Data and Analysis Center for Software, Rome Air Development Center, Griffins AFB, New York, 1979.  via [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

207 rows

**P38.csv**
 Musa J. D., A. Iannino, and K. Okumoto, "Software Reliability: Measurement, prediction, application", 1987, McGraw-Hill book company.

17 rows

Computer monitoring system for nuclear reactors with an estimated 5,000 installations running 24 hr/day over 43 calendar months.  Use_time is years of operation, Elapsed_time is months.

**T1.csv**
 Musa J. D., A. Iannino, and K. Okumoto, "Software Reliability: Measurement, prediction, application", 1987, McGraw-Hill book company.

136 rows

**T38.csv**
 Musa J. D., A. Iannino, and K. Okumoto, "Software Reliability: Measurement, prediction, application", 1987, McGraw-Hill book company.

11 rows

Data collected weekly, with test time in cpu hours.

**T39.csv**
 Musa J. D., A. Iannino, and K. Okumoto, "Software Reliability: Measurement, prediction, application", 1987, McGraw-Hill book company.

19 rows

Data collected weekly, with test time in cpu hours.

**Musa-15_5.csv**
 Musa J. D., A. Iannino, and K. Okumoto, "Software Reliability: Measurement, prediction, application", 1987, Table 15.5, McGraw-Hill book company.

163 rows

Listed as System 40 in Musa, J.D., "Software Reliability Data"

Military software system developed by eight programmers, delivering 48,412 executable object code instructions.

**J1.csv**
Nikora A. P. and M. R. Lyu, "Software Reliability Measurement Experience", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

62 rows

**J2.csv**
Nikora A. P. and M. R. Lyu, "Software Reliability Measurement Experience", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

181 rows

**J3.csv**
Nikora A. P. and M. R. Lyu, "Software Reliability Measurement Experience", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

41 rows
n
**J4.csv**
Nikora A. P. and M. R. Lyu, "Software Reliability Measurement Experience", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

114 rows

**J5.csv**
Nikora A. P. and M. R. Lyu, "Software Reliability Measurement Experience", in [Handbook of Software Reliability Engineering](https://www.cse.cuhk.edu.hk/~lyu/book/reliability/) ed Michael R. Lyu

73 rows

**PL1_db.csv**
Ohba M., "Software reliability analysis models," IBM Journal of Research and Development, pp 428-442, Vol 28(4), Jul 1984.

19 rows

The system is a PL/I database application software consisting of approximately 1,317,000 lines of code.  Each row contains cumulative faults/CPU time for consecutive elapsed weeks.

**Ohba84-hcp.csv**
Ohba M., "Software reliability analysis models," IBM Journal of Research and Development, pp 428-442, Vol 28(4), Jul 1984.

The system is consists of three software modules of a hardware control program. The size of the combined system is approximately 35,000 lines of code.  The test data are reported for individual modules as well as the combined system.

10 rows

**singsys_40.csv**
Singpurwalla N. D., "Software Reliability Modeling by Concatenating Failure Rates," Proceedings Ninth International Symposium on Software Reliability Engineering, 1998, pages 106-110.  The cited source is Musa's "Software Reliability Data," DACS report, and say it comes from System 40.

100 rows

**stucki_tI.csv**
Stucki L. G., Moranda P., Foshee G, and Omre R., "Final Report A Methodology for Producing Reliable Software vol I", Mar 1976, MDC G6210, McDonnell-Douglas Astronautics Company-West.  Who cites the source: Wagoner, W. L., "The Final Report on a Software Reliability Measurement Study," Report #TOR-0074 (4112)-1, Aerospace Corporation.

15 rows

Errors recorded during a period while the debugging of a data-reduction program, called the F11-D Program, consisting of "approximately 3-4 thousand" Fortran statements, consuming given CPU time during the period.

**tohma89_t1.csv**
Tohma Y., Jacoby R., Murata Y., and Yamamoto M., "Hyper-Geometric Distribution Model to Estimate the Number of Residual Software Faults", 1989, Proceedings of the Thirteenth Annual International Computer Software & Applications Conference.

111 rows

The software system is a monitoring and real-time control system and consists of 200,000 lines of code. The cumulative test time is reported in days.

**tohma89_t3.csv**
Tohma Y., Jacoby R., Murata Y., and Yamamoto M., "Hyper-Geometric Distribution Model to Estimate the Number of Residual Software Faults", 1989, Proceedings of the Thirteenth Annual International Computer Software & Applications Conference.

22 rows

The software system is a monitoring and real-time control system and consists of 200,000 lines of code. The cumulative test time is reported in days.

**tohma89_t5.csv**
Tohma Y., Jacoby R., Murata Y., and Yamamoto M., "Hyper-Geometric Distribution Model to Estimate the Number of Residual Software Faults", 1989, Proceedings of the Thirteenth Annual International Computer Software & Applications Conference.

46 rows

The software system is a monitoring and real-time control system and consists of 200,000 lines of code. The cumulative test time is reported in days.

**tohma91_t1.csv**
Tohma Y., Yamano H., Ohba M., and Jacoby R., "Parameter Estimation of the Hyper-Geometric Distribution Model for Real Test/Debug Data", 1991, International Symposium on Software Reliability Engineering.

109 rows

The software system is for a real-time control application consisting of 870,000 lines of code.  The cumulative test time is reported in days.

**tohma89_tV.csv**
Tohma Y., Tokunaga K., Nagase S., and Murata Y., "Structural Approach to the Estimation of the Number of Residual Software Faults Based on the Hyper-Geometric Distribution", IEEE Transactions on Software Engineering, Vol 15(3), pages 345-355, March 1989.

199 rows

The software system is a railway interlocking system and has about 14,500 assembly instructions. The cumulative test time is reported in days.

**Xie_T1.csv**
Xie M., Q. P. Hu, Y. P. Wu and S. H. Ng, "A Study of the Modeling and Analysis of Software Fault-detection and Fault-correction Processes," Quality and Reliability Engineering International, Vol 23(4), pages 459-470, 2007.

17 rows

Faults detected and corrected in each week.

**westgate_F1.csv**
Westgate C. J., "Validation of an Exponentially Decreasing Failure Rate Software Reliability Model," MSc. thesis, Sep 1989.

197 rows

Space system.  Failures with DOD severity code of 1 (System Abort. A software of firmware problem that results in a system abort.) or 2(System Degraded. No Work-around. A software of firmware problem that severely degrades the system and no alternative work-around exists (program restarts not acceptable)).  Date gives when the fault was discovered.

**westgate_F2.csv**
Westgate C. J., "Validation of an Exponentially Decreasing Failure Rate Software Reliability Model," MSc. thesis, Sep 1989.

16 rows

Aircraft system.  Failures with DOD severity code of 1 (System Abort. A software of firmware problem that results in a system abort.) or 2(System Degraded. No Work-around. A software of firmware problem that severely degrades the system and no alternative work-around exists (program restarts not acceptable)).  Date gives when the fault was discovered.

**westgate_F3.csv**
Westgate C. J., "Validation of an Exponentially Decreasing Failure Rate Software Reliability Model," MSc. thesis, Sep 1989.

199 rows

Communication system.  Failures with DOD severity code of 1 (System Abort. A software of firmware problem that results in a system abort.) or 2(System Degraded. No Work-around. A software of firmware problem that severely degrades the system and no alternative work-around exists (program restarts not acceptable)).  Date gives when the fault was discovered.

**westgate_F4.csv**
Westgate C. J., "Validation of an Exponentially Decreasing Failure Rate Software Reliability Model," MSc. thesis, Sep 1989.

202 rows

Communication system. a Failures with DOD severity code of 1 (System Abort. A software of firmware problem that results in a system abort.) or 2(System Degraded. No Work-around. A software of firmware problem that severely degrades the system and no alternative work-around exists (program restarts not acceptable)).  Date gives when the fault was discovered.

**westgate_F5.csv**
Westgate C. J., "Validation of an Exponentially Decreasing Failure Rate Software Reliability Model," MSc. thesis, Sep 1989.

409 rows

Space system.  Failures with DOD severity code of 1 (System Abort. A software of firmware problem that results in a system abort.) or 2(System Degraded. No Work-around. A software of firmware problem that severely degrades the system and no alternative work-around exists (program restarts not acceptable)).  Date gives when the fault was discovered.

**westgate_F6.csv**
Westgate C. J., "Validation of an Exponentially Decreasing Failure Rate Software Reliability Model," MSc. thesis, Sep 1989.

115 rows

Space system.  Failures with DOD severity code of 1 (System Abort. A software of firmware problem that results in a system abort.) or 2(System Degraded. No Work-around. A software of firmware problem that severely degrades the system and no alternative work-around exists (program restarts not acceptable)).  Date gives when the fault was discovered.

**Wood_T3-1.csv**
Wood A., "Software Reliability Growth Models", Technical Report 96.1, Sep 1996, Tandem Computers.

70 rows

Data from four separate software releases.  Data has been scaled by artificially setting the execution time in Release 1 to 10,000 hours and the number of defects discovered in Release 1 to 100 and ratioing all other data proportionately  All data was ratioed proportionately, e.g., all test hours were multiplied by 10,000 and divided by the real number of test hours from Release 1.

**Wood_T3-9.csv**
Wood A., "Software Reliability Growth Models", Technical Report 96.1, Sep 1996, Tandem Computers.

31 rows

TPR, Total Problem reports from releases 2 and 3.  Data has been scaled by artificially setting the execution time in Release 1 to 10,000 hours and the number of defects discovered in Release 1 to 100 and ratioing all other data proportionately  All data was ratioed proportionately, e.g., all test hours were multiplied by 10,000 and divided by the real number of test hours from Release 1.
