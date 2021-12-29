# Omega Corps

Local network management project.

## Naming Convention

Each device follows the following pattern:

```
us1a-rpaaa-cs000001
           || ^^^^^^ id/number
           ^^ group/zone (specific for orgs)
         ^ architecture (a for arm64, x for x86_64)
     ^^^^ vendor code
^^^^ dc/az
```

Example:

```
us1a-rpaaa-cs000001.omegacorps.local
```

Means:

1. Host is located in US1 data center
2. Host is located in US1a availability zone
3. Host is Raspberry PI device
4. Host is Raspberry PI config code 'aa' (can do lookup to see generation and configuration)
5. Host is arm64 architecture
6. Host belongs to Compute Service group
