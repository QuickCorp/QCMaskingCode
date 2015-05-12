# QCMaskingCode
Quick Corp Code Generator

#Step 1:
Run in console:
> pip install qcmaskingcode

# Step 2:
Include in your code the following lines:
> import qcmaskingcode as qcm
> qcm.generate2(1234)
This generates a representative masking code to 1234

# Step 3:
For revert the code:
> qcm.revert2(generatedCode)
When 'generatedCode' is a maskingcode generated with qcm.generate2()
