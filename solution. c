#include <stdio.h>

int sockMerchant(int n, int ar[]) {
    int count[101] = {0}; // Array to store the count of each color
        int pairs = 0;
            
                // Count the occurrence of each color
                    for (int i = 0; i < n; i++) {
                            count[ar[i]]++;
                                }
                                    
                                        // Calculate the number of pairs
                                            for (int i = 1; i <= 100; i++) {
                                                    pairs += count[i] / 2;
                                                        }
                                                            
                                                                return pairs;
                                                                }
                                                                
                                                                int main() {
                                                                    int n;
                                                                        scanf("%d", &n);
                                                                            
                                                                                int ar[n];
                                                                                    for (int i = 0; i < n; i++) {
                                                                                            scanf("%d", &ar[i]);
                                                                                                }
                                                                                                    
                                                                                                        int pairs = sockMerchant(n, ar);
                                                                                                            printf("%d\n", pairs);
                                                                                                                
                                                                                                                    return 0;
                                                                                                                    }
                                                                                                                    
                                                                                                                    
