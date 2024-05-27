# CoolSwap template

### Rinkeby

- Factory: 0x6Bd5A1A63ffF10De3c6B7C667040E9AE1B47fDf2
- Router: 0xA4E1f3fD10E2397f58926E215Ed331D7cDA14056
- Pair hash: 0xaf88dd15a55596feb9d67243c727bfd6144af12453963809bc91f0cfcf8241bc



{
  "compilerOptions": {
    "target": "es5",
    "lib": ["dom", "dom.iterable", "esnext"],
    "allowJs": true,
    "skipLibCheck": true,
    "forceConsistentCasingInFileNames": true,
    "noEmit": true,
    "esModuleInterop": true,
    "module": "esnext",
    "strict": false,
    "alwaysStrict": false,
    "strictNullChecks": false,
    "noUnusedLocals": true,
    "noFallthroughCasesInSwitch": true,
    "noImplicitAny": false,
    "noImplicitThis": true,
    "noImplicitReturns": true,
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "jsx": "preserve",
    "downlevelIteration": true,
    "allowSyntheticDefaultImports": true,
    "types": ["react-spring", "jest"],
    "baseUrl": "src"
  },
  "exclude": ["node_modules"],
  "include": ["./src/**/*.ts", "./src/**/*.tsx", "src/components/Confetti/index.js"]
}
