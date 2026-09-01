# hi {
  "type": "object",
  "properties": {
    "investigationNumber": {
      "type": "string"
    },
    "reviewer": {
      "type": "string"
    },
    "ciName": {
      "type": "string"
    },
    "totalScore": {
      "type": "integer"
    },
    "totalQuestions": {
      "type": "integer"
    },
    "percentage": {
      "type": "number"
    },
    "result": {
      "type": "string"
    },
    "answers": {
      "type": "object",
      "additionalProperties": {
        "type": "string"
      }
    }
  },
  "required": [
    "investigationNumber",
    "reviewer",
    "ciName",
    "totalScore",
    "totalQuestions",
    "percentage",
    "result",
    "answers"
  ]
}
