import pandas as pd

def multiply_ten_by_ten():
    results = [10 * 10 for _ in range(10)]
    return results

def save_results_to_excel(results):
    df = pd.DataFrame(results, columns=["Result"])
    df.to_excel("results.xlsx", index=False)

if __name__ == "__main__":
    results = multiply_ten_by_ten()
    save_results_to_excel(results)
