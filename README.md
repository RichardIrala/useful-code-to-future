# useful-code-to-future

# For the next code
* Tailwind v3 required

## Code

#### Image that when you hover it, a description appears in the lower left part

```html
<div className="relative group w-[11.25rem] h-60 min-w-[11.25rem] overflow-hidden">
  <img
    src="/images/nft.png"
    alt="NFT"
    className="w-full h-full object-cover rounded-[12px] border border-transparent group-hover:border-gold transition-all duration-300 ease-in-out"
  />

  <div className="absolute bottom-4 left-4 transform translate-y-full group-hover:translate-y-0 transition-all duration-300 ease-in-out flex items-center space-x-4">
    <img
      src="/images/nft.png"
      alt="nft"
      className="w-8 h-8"
    />
    <span className="text-white">Dorado</span>
  </div>
</div>
```
