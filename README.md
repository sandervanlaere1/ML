# Machine Learning for Life Sciences
Repository for the predictive modeling course at UGent.

## Best practices
- Jupyter notebooks on GitHub can be linked to colab and shared with students without having to upload to Drive. In colab: "Open > GitHub" and copy link. Then, on Ufora: add hyperlink.
- Separate versions for unsolved and solved. Solved versions are to be published to students after lab.
- Uploading the data to GitHub and using `urllib` to download them ensures that all students seamlessly access the data without having to download separate files and will work on all platforms (unlike using `!wget`). Example:

```python
import urllib.request
urllib.request.urlretrieve("datafile_url", "downloaded_file_location")
```

- Like-wise, embedding images from the net is best practice: `<img src="link" width = x>`.
