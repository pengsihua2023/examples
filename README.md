## Examples
We host a wide range of example scripts for multiple learning frameworks. Simply choose your favorite: [PyTorch](https://github.com/huggingface/transformers/tree/main/examples/pytorch), [TensorFlow](https://github.com/huggingface/transformers/tree/main/examples/tensorflow).  

We also have some [research projects](https://github.com/huggingface/transformers/tree/main/examples/research_projects), as well as some [legacy examples](https://github.com/huggingface/transformers/tree/main/examples/legacy). Note that unlike the main examples these are not actively maintained, and may require specific older versions of dependencies in order to run.  

While we strive to present as many use cases as possible, the example scripts are just that - examples. It is expected that they won't work out-of-the box on your specific problem and that you will be required to change a few lines of code to adapt them to your needs. To help you with that, most of the examples fully expose the preprocessing of the data, allowing you to tweak and edit them as required.  

Please discuss on the [forum](https://discuss.huggingface.co/) or in an [issue](https://github.com/huggingface/transformers/issues) a feature you would like to implement in an example before submitting a PR; we welcome bug fixes, but since we want to keep the examples as simple as possible it's unlikely that we will merge a pull request adding more functionality at the cost of readability.    

### Important note  
#### Important  

To make sure you can successfully run the latest versions of the example scripts, you have to install the library from source and install some example-specific requirements. To do this, execute the following steps in a new virtual environment:  
```
git clone https://github.com/huggingface/transformers  
cd transformers  
pip install .  
```
Then cd in the example folder of your choice and run  
```
pip install -r requirements.txt
```
To browse the examples corresponding to released versions of Transformers, click on the line below and then on your desired version of the library: 

<details>
<summary>Examples for older versions of Transformers</summary>
  
- v4.21.0
- v4.20.1
v4.19.4
v4.18.0
v4.17.0
v4.16.2
v4.15.0
v4.14.1
v4.13.0
v4.12.5
v4.11.3
v4.10.3
v4.9.2
v4.8.2
v4.7.0
v4.6.1
v4.5.1
v4.4.2
v4.3.3
v4.2.2
v4.1.1
v4.0.1
v3.5.1
v3.4.0
v3.3.1
v3.2.0
v3.1.0
v3.0.2
v2.11.0
v2.10.0
v2.9.1
v2.8.0
v2.7.0
v2.6.0
v2.5.1
v2.4.0
v2.3.0
v2.2.0
v2.1.1
v2.0.0
v1.2.0
v1.1.0
v1.0.0
  
</details>

Alternatively, you can switch your cloned Transformers to a specific version (for instance with v3.5.1) with  
```
git checkout tags/v3.5.1
```
and run the example command as usual afterward.  
