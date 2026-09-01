CI Name:
@{body('Parse_JSON')?['ciName']}

Total Score:
@{outputs('Calculate_Total_Score')}

Total %:
@{formatNumber(outputs('Calculate_Percentage'),'0.00')}%

Result:
@{outputs('Calculate_Result')}
