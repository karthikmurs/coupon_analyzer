# 📝 Coupon Acceptance & Rejection Report

## High level Summary

From the analysis we did on a few datapoints, the coupon acceptance is highly stratified and driven by two main factors: **Coupon Type** and **Friction**.

* **Coupon Type is Critical:** Acceptance rates range widely, from over 73% for cheap take-out to under 39% for coffee.
* **Targeting is Key for Low-Acceptance Coupons (e.g., Bar):** For Bar coupons, highly specific demographic targeting increases acceptance from a baseline of 41% to over **71%**.
* **Friction Drives Rejection:** Poor **Weather**, **Long Travel Times**, and **Counter-Directional** trips are the primary reasons customers reject coupons, regardless of the coupon type.

***

## 1. Acceptance Rates by Coupon Type

The most immediate predictor of acceptance is the coupon type itself. Coupons for **cheap, convenient food** are overwhelmingly accepted.

| Rank | Coupon Type | Overall Acceptance Rate | Observation |
| :--- | :--- | :--- | :--- |
| 1 | **Carry out & Take away** | **73.55%** | Highest acceptance rate—indicates high demand for convenience/cheap food. |
| 2 | **Restaurant (<20)** | **70.28%** | Very high acceptance for low-cost sit-down options. |
| 4 | **Bar** | **41.00%** | Low acceptance; requires careful targeting. |
| 5 | **Coffee House** | **38.81%** | Lowest acceptance; suggest low perceived value for the effort. |

***

## 2. Targeted Acceptance (The Bar Coupon Case Study)

For low-acceptance coupons like the Bar coupon (baseline 41.00% acceptance), specific targeting is extremely effective.

### Target Acceptor Profile (Group A)

Customers are most likely to accept the Bar coupon if they meet these three criteria:

1.  **Frequent Behavior:** Visit a bar **more than once a month** (1-3 times or more).
2.  **Situation:** Do **not have a child** as a passenger.
3.  **Profession:** Are **not** in a Farming, Fishing, or Forestry occupation.

| Group | Acceptance Rate | Difference vs. Rejectors |
| :--- | :--- | :--- |
| **Target Acceptors** (Meeting all three criteria) | **71.32%** | **+41.72 percentage points** |
| **All Other Drivers** (The Rejector Baseline) | 29.60% | |

**Conclusion:** Targeted marketing using these three filters isolates a group **2.4 times more likely** to accept the coupon.

***

## 3. Rejection Analysis: The Friction Points

Rejection is heavily influenced by environmental and logistical friction across all coupon types.

### Rejection by Travel Time

Longer travel times create the highest friction, acting as the largest barrier to redemption.

| Required Travel Time | Rejection Rate | Impact |
| :--- | :--- | :--- |
| **>= 25min** | **57.11%** | Highest friction point—drivers reject over half the time. |
| >= 15 minutes but <= 25 minutes | 43.93% | Medium rejection. |
| **< 15 minutes** | **38.58%** | Lowest rejection rate. |

### Rejection by Weather

Inclement weather significantly decreases a customer's willingness to stop for a coupon.

| Weather Condition | Rejection Rate |
| :--- | :--- |
| **Rainy** | **53.72%** |
| **Snowy** | 52.95% |
| **Sunny** | 40.52% |

### Rejection by Time of Day

| Time Slot | Rejection Rate |
| :--- | :--- |
| **Evening/Night (6PM, 10PM)** | **20.87%** |
| Morning/Day (7AM, 10AM, 2PM) | 29.79% |

***

## Key Takeaways (for running campaigns)

1.  **Prioritize Location:** To maximize redemption, coupons must require less than **25 minutes** of travel time. Ideally, they should require **less than 15 minutes**.
2.  **Avoid Bad Weather:** Expect a **~13 percentage point drop** in redemption during rain or snow.
3.  **Use Target Profiles:** For Bar and Coffee coupons, use the defined high-frequency/low-resistance demographic profiles to maximize ROI.