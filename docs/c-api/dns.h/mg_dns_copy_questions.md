---
title: "mg_dns_copy_questions()"
decl_name: "mg_dns_copy_questions"
symbol_kind: "func"
signature: |
  int mg_dns_copy_questions(struct mbuf *io, struct mg_dns_message *msg);
---

Append already encoded questions from an existing message.

This is useful when generating a DNS reply message which includes
all question records.

Return number of appened bytes. 

