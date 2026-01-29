focused on understanding state estimation and filtering techniques, specifically the Kalman Filter, and how parameter choices affect prediction accuracy and responsiveness in noisy systems.
explored the theoretical foundations of recursive state estimation and studied the provided Week 3 resources to build intuition around process noise, measurement noise, uncertainty propagation, and Kalman gain behavior. Then implemented and experimented with Kalman filtering through coding notebooks and parameter exploration tasks.

Key areas of analysis included:

Measurement noise (R): Increasing R reduced trust in measurements and increased reliance on model predictions, resulting in smoother estimates and smaller Kalman gains.

Process noise (Q): Increasing Q reduced confidence in the prediction model, making the filter more responsive to measurements but producing noisier estimates.

Initial uncertainty (P): Larger P values caused the filter to adapt quickly to measurements, while smaller P delayed convergence due to lower initial Kalman gain.

Incorrect initial state: Verified that the filter can still converge to the true state when process noise is non-zero, demonstrating robustness.