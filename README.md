# 042 Null Coalescing Operator

## Lecture

NO VIDEO ON YOUTUBE CURRENTLY
[![# Null Coalescing Operator)](https://img.youtube.com/vi/v1dbW26xRQQ/0.jpg)](https://www.youtube.com/watch?v=v1dbW26xRQQ)

## Instructions

- In `HomeEnergyApi/Security/ValueEncryptor`
  - Modify the `Encrypt()` method
    - Change the arguments so that it takes an argument of `string?` rather than `string`
    - If the `string? plainText` argument is null, `"default"` should be passed to `swEncrypt.Write()`
    - Otherwise, `plainText` should be passed as it currently is now

## Additional Information

- Do not remove or modify anything in `HomeEnergyApi.Tests`
- Some Models may have changed for this lesson from the last, as always all code in the lesson repository is available to view
- Along with `using` statements being added, any packages needed for the assignment have been pre-installed for you, however in the future you may need to add these yourself

## Building toward CSTA Standards:

## Resources
- https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/operators/null-coalescing-operator

Copyright &copy; 2025 Knight Moves. All Rights Reserved.
