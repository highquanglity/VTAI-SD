\begin{table}[ht]
	\centering
	\caption{So sánh các mô hình VLM và khả năng hỗ trợ tiếng Việt theo OpenVLM Leaderboard \cite{leaderboard}}
	\resizebox{\textwidth}{!}{%
		\begin{tabular}{c|l|c|l|l|c|c}
			\toprule
			\textbf{Rank} & \textbf{Method} & \textbf{Param (B)} & \textbf{Language Model} & \textbf{Vision} & \textbf{Avg score} & \textbf{Tiếng Việt} \\
			\midrule
			1 & Ristretto-3B & 3.84 & Qwen2.5-3B & SigLIP-400M & 67.7 & \ding{51} \\
			2 & SAIL-VL-1.5-2B & 2.47 & Qwen2.5-1.5B & AIMv2 Huge & 67.0 & \ding{51} \\
			\hline\hline
			1 & InternVL3-8B & 7.94 & Qwen2.5-7B & InternViT-300M-v2.5 & 73.6 & \ding{51} \\
			2 & SAIL-VL-1.6-8B & 8.33 & Qwen2.5-7B & AIMv2 Huge & 73.6 & \ding{51} \\
			\hline\hline
			1 & InternVL3-14B & 15.1 & Qwen2.5-14B & InternViT-300M-v2.5 & 75.2 & \ding{51} \\
			2 & Ovis2-16B & 16.2 & Qwen2.5-14B & AIMv2 Huge & 73.3 & \ding{51} \\
			\bottomrule
		\end{tabular}%
