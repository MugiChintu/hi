# hi 
<p>
A quality review has identified the following remark for Investigation
<b>@{body('Parse_JSON')?['investigationNumber']}</b>:
</p>

<p style="color:red; font-weight:bold;">
@{body('Parse_JSON')?['remark']}
</p>

<h3>Case Details Report</h3>

<table style="border-collapse:collapse; width:100%; font-family:Arial, sans-serif; font-size:14px;">
    <tr>
        <th style="background-color:#4472C4; color:white; border:1px solid #808080; padding:8px; text-align:center;">
            Field
        </th>
        <th style="background-color:#4472C4; color:white; border:1px solid #808080; padding:8px; text-align:center;">
            Result
        </th>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">CI Name</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['ciName']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">All Actions Addressed Accurately?</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['allActionsAddressedAccurately']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Were Product Return Actions and DDs Closed Accurately?</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['productReturnActionsAndDDsClosedAccurately']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Manufacture Date</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['manufactureDate']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Were Needed Files Uploaded?</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['neededFilesUploaded']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Were Files Properly Named?</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['filesProperlyNamed']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Coding / Product Analysis</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['codingProductAnalysis']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Labelling Review</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['labellingReview']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">DHR Review</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['dhrReview']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Service History Review</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['serviceHistoryReview']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Risk Review</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['riskReview']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Complaint History Review</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['complaintHistoryReview']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">CAPA History Review</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['capaHistoryReview']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">QMS / CAPA / NCR Record Input</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['qmsCapaNcrRecordInput']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Escalation Determination</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['escalationDetermination']}
        </td>
    </tr>

    <tr>
        <td style="border:1px solid #808080; padding:7px;">Investigation Summary</td>
        <td style="border:1px solid #808080; padding:7px;">
            @{body('Parse_JSON')?['investigationSummary']}
        </td>
    </tr>

    <tr>
        <td style="background-color:#E2F0D9; border:1px solid #808080; padding:8px; font-weight:bold;">
            Total Score
        </td>
        <td style="background-color:#E2F0D9; border:1px solid #808080; padding:8px; font-weight:bold;">
            @{body('Parse_JSON')?['totalScore']}
        </td>
    </tr>

    <tr>
        <td style="background-color:#E2F0D9; border:1px solid #808080; padding:8px; font-weight:bold;">
            Total %
        </td>
        <td style="background-color:#E2F0D9; border:1px solid #808080; padding:8px; font-weight:bold;">
            @{body('Parse_JSON')?['totalPercentage']}%
        </td>
    </tr>

    <tr>
        <td style="background-color:#E2F0D9; border:1px solid #808080; padding:8px; font-weight:bold;">
            Pass or Fail
        </td>
        <td style="background-color:#E2F0D9; border:1px solid #808080; padding:8px; font-weight:bold;">
            @{body('Parse_JSON')?['passOrFail']}
        </td>
    </tr>
</table>
