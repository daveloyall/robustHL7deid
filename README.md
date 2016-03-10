# robustHL7deid
This tool deids HL7 messages for troubleshooting purposes.

## Goals
Don't lose any information beyond what is required by law/common sense.

Let's say a batch contains 100 ELR and exactly 32 of them are about the same person while the 
rest are about different people.   Naive de-id tools would 'lose' that information--the fact
that there were 32 messages about the same person.  The information would be lost when every
name in the file gets set to JOHN DOE.  It is possible to preserve 'number of occurances'
information without violating anyone's privacy.

## Features

### 
