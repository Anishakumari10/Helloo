var list =List("when($RECORD_NB===' ',lpad($RECORD_NB,10,' ')).otherwise(lpad($RECORD_NB,10,'0')) as RECORD_NB",
"when($SEQUENCE_NB===' ',lpad($SEQUENCE_NB,9,' ')).otherwise(lpad($SEQUENCE_NB,9,'0')) as SEQUENCE_NB","when($P13_CNTL===' ',lpad($P13_CNTL,3,' ')).otherwise(lpad($P13_CNTL,3,'0')) as P13_CNTL","when($TRADE_DATE===' ',rpad($TRADE_DATE,8,' ')).otherwise(rpad($TRADE_DATE,8,' ')) as TRADE_DATE"
)
