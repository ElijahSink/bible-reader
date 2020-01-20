### Daily Reading

A project that assists daily Bible readings from a written plan.

## Reading plans

Reading plans are specified in .plan files, which are simply JSON. The file should follow this pattern:
```
{
    "name": "My plan",
    "author": "Author's Name",
    "cursors": [{
            "start": "Genesis 1"
            "end": "Deuteronomy 34",
            "increment": 1,
            "position": 0
        }, {
            "start": "Joshua 1",
            "end": "Esther 10",
            "increment": 1,
            "position": 0
        }, {
            "start": "Job 1",
            "end": "Song of Solomon 1",
            "increment": 1,
            "position": 0
        }, {
            "start": "Isaiah 1",
            "end": "Malachi 4",
            "increment": 1,
            "position": 0
        }, {
            "start": "Matthew 1",
            "end": "John 21",
            "increment": 1,
            "position": 0
        }, {
            "start": "Acts 1",
            "end": "Revelation 22",
            "increment": 1,
            "position": 0
        }
    ]
}
```
