You can mock an inexistent object using mock.patch with an param create=True.

@mock.patch('object', inexistent_dict', create=True, return_value=dict(k='v'))

Refs:
https://docs.python.org/3/library/unittest.mock.html