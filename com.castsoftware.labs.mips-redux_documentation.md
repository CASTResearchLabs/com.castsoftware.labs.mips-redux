# _com.castsoftware.labs.mips-redux_ Description
This extension provides computation of the following new assessment indicator(s)
* the *MIPS Reduction index*
* supporting Technical Criteria

##  Problem Statement
...
MIPS can be saved by making Software more efficient

## Research Labs proposal
To identify pieces of Software that could be optimized to withstand unexpected workload, increased "scrutiny" from hackers, "seamless" evolution of execution environment, the Research Labs offer a solution based on CAST AIP Assessment Model.
*  The *MIPS Reduction Index* is a Business Criterion that aggregates impactful mainframe Quality Rules from Efficiency- and Robustness-related Technical Criteria
*  grouped into new dedicated Technical Criteria

The Research Labs released this first version of the MIPS Reduction Index to leverage the expertise and experience of customers in order to fine-tune its exact composition and collect feedback.

## Formula
The MIPS Reduction Index is based on the following Technical Criteria
* MIPS Reduction - focus on data access efficiency
* MIPS Reduction - focus on algorithmic costs
* MIPS Reduction - focus on avoiding transaction failure


The Technical Criteria have been populated with Quality Rules with aggregate weight greater or equal to 5 of the following existing Technical Criteria:
* Efficiency – Expensive Calls in Loops
* Efficiency – SQL and Data Handling Performance
* Programming Practices – Error and Exception Handling
* Programming Practices – Unexpected Behavior


# In what situation should you install this extension?
If you are interested in getting a preview of what the MIPS Reduction index would be and are willing to share the results to help the CAST Research Labs validate them.

# Release notes
N/A

# _com.castsoftware.labs.mips-redux_ technology support
Mainframe technology only is supported (by design).

# Function Point, Quality and Sizing support
This extension is designed to bring new quality indicator aside existing ones.

# CAST AIP compatibility

This extension is compatible with:
* 8.1.x out-of-the-box (AIP release used for the tests)
* 8.0.x after changing the nuspec file (there is no reason the extension would not work but it was not tested)
* 7.x.x after changing the nuspec file (there is no reason the extension would not work but it was not tested)

# Supported DBMS servers
This extension is currently supported on CAST databases installed on any supported RDBMS.


# Prerequisites
* An installation of any compatible release of CAST AIP (see table above)


# Bug Fix List
N/A

# Download and installation instructions

Please see:  [Extension Link Installation](http://doc.castsoftware.com/display/DOCEXT/Extension+download+and+installation)

The installation steps are the following:
* download the extension through the CAST Extension Downloader
* open Server Manager 8.1+
* select the existing set of databases to update / install a new set of databases
* manage extensions of the existing set of database / follow the installation wizard up to the manage extension pane
* select _com.castsoftware.labs.mips-redux.2.0.0_
* run the update / the installation  
* open CAST Management Studio
* import the Assessment Model from the Dashboard Service processed in steps #3 to #6 above; this is a *Mandatory* step to start computing the new indicator, one MUST import and use the Assessment Model from the Dashboard that was updated with the extension

# Packaging, delivering and analyzing your source code
Packaging, delivering and analyzing your source code is performed the same way as usual.

To get results:
* run a new snapshot (if not possible, contact the Research Labs for alternative procedure)

To avoid computing the MIPS Reduction index for applications that are not candidate to MIPS reduction:
* open CAST Management Studio
* edit the Dashboard Service(s) you are publishing the Snapshots of the N/A application(s)
* select the Assessment Model tab
* create an exclusion for the MIPS Reduction index and the N/A application(s)

# What results can you expect?

## Objects
N/A

## Links
N/A

## Quality rules
N/A

## Technical Criteria
List of new Technical Criteria
* MIPS Reduction - focus on data access efficiency
* MIPS Reduction - focus on algorithmic costs
* MIPS Reduction - focus on avoiding transaction failure

## Business Criteria
List of new Business Criteria
* MIPS Reduction index

# Limitations
N/A
