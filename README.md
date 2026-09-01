concat(
  body('Parse_JSON')?['investigationNumber'],
  '-',
  formatDateTime(utcNow(),'yyyyMMddHHmmss')
)
