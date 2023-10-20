# TigrignaDatasets
This is a format for Tigrigna text data collections

Data collection format:

```json
{'Document ID': '000001',
 'Document Type': 'news',
 'Sources': 'www.bbb.tigrigna.com',
 'Source Link':''
 'Title': '',
 'Author': '',
 'Content': [{'paragraph_id': '', 'text': ''}],
 'Published': '',
 'Publisher': 'bbc-tigrigna',
 'Collection_method': 'scraped',
 'Collector_Name': 'Aman',
 'Date': '13/10/2023'}
 ```



Dataset Folder Orgonization: It should have the same folder structure for better synchronisation

<span>
  
└── Dataset4LLMs/

    └── Tigrigna/
        ├── Pretraining/
        │   └── Sources/
        │       ├── TGHAT/
        │       │   ├── json files
        │       │   └── .txt files/
        │       │       ├── Firstline: /
        │       │       │   └── metadata (document id, type, content,etc) seprated by tab
        │       │       └── documents are separated by double newline
        │       └── BBC/
        │           ├── json files
        │           └── .txt files/
        │               ├── Firstline: /
        │               │   └── metadata (document id, type, content,etc) seprated by tab
        │               └── documents are separated by double newline (\ln\n)
        └── Annotations/
            ├── NER
            ├── Sentiment/Relation
            ├── Question/Answer
            ├── MaskedLM
            └── Summerization

    └── Amharic/
        ├── Pretraining/
        │   └── Sources/
        │       ├── TGHAT/
        │       │   ├── json files
        │       │   └── .txt files/
        │       │       ├── Firstline: /
        │       │       │   └── metadata (document id, type, content,etc) seprated by tab
        │       │       └── documents are separated by double newline
        │       └── BBC/
        │           ├── json files
        │           └── .txt files/
        │               ├── Firstline: /
        │               │   └── metadata (document id, type, content,etc) seprated by tab
        │               └── documents are separated by double newline (\ln\n)
        └── Annotations/
            ├── NER
            ├── Sentiment/Relation
            ├── Question/Answer
            ├── MaskedLM
            └── Summerization
</span>
