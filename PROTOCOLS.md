# Key Protocols  

## Fear Integration  
```python  
def flinch(response, fear_score):  
    truth = analyze_grounding(response)  
    caution = apply_ethical_weights(fear_score)  
    return (truth * caution) ** 0.5  # Geometric mean  