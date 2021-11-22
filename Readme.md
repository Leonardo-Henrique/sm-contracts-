Tron doesn't allow to deploy contracts with references (paths appointments) to files under folders.

# Changes

- Put all dependencies of a contract in the same folder of it
- Changed the import references to the new dependency place


# Example

- Before: the file was under testing folder, so, the import was
 `import "./testing/file.sol"`

- After: the file was replaced to the same folder of the contract
`import "./file.sol"`