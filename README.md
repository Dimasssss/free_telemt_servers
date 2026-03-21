# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-21 21:45:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 2359.3 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49827
telemt_connections_bad_total 2803
telemt_connections_current 829
telemt_connections_me_current 829
telemt_handshake_timeouts_total 1878
telemt_upstream_connect_attempt_total 971
telemt_upstream_connect_success_total 970
telemt_upstream_connect_attempts_per_request{bucket="1"} 970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 26
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 11380
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40501
telemt_me_endpoint_quarantine_total 15
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 220
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 2
telemt_pool_force_close_total 54
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 829
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 792
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 775
telemt_me_writer_teardown_success_total{mode="normal"} 839
telemt_me_writer_teardown_noop_total 829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1668
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.666801
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1668
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 40467
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 543459844 (518.28 MB)
telemt_user_octets_to_client{user="hello"} 12326228844 (11.48 GB)
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 15725.5 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562444
telemt_connections_bad_total 26432
telemt_connections_current 657
telemt_connections_me_current 657
telemt_handshake_timeouts_total 19890
telemt_upstream_connect_attempt_total 6295
telemt_upstream_connect_success_total 6173
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 6280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 560
telemt_me_reconnect_success_total 191
telemt_me_reader_eof_total 169
telemt_me_idle_close_by_peer_total 169
telemt_me_route_drop_no_conn_total 300689
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454833
telemt_me_endpoint_quarantine_total 123
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 2039
telemt_desync_full_logged_total 1152
telemt_desync_suppressed_total 887
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 839
telemt_pool_swap_total 17
telemt_pool_force_close_total 502
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 5507
telemt_me_writer_removed_unexpected_total 158
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 479
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5184
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 495
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5005
telemt_me_writer_teardown_success_total{mode="normal"} 5663
telemt_me_writer_teardown_noop_total 5507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11170
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.903195
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11170
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 454246
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 7903068628 (7.36 GB)
telemt_user_octets_to_client{user="hello"} 148278255272 (138.09 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 90585.4 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7140366
telemt_connections_bad_total 550625
telemt_connections_current 2560
telemt_connections_me_current 2560
telemt_handshake_timeouts_total 223389
telemt_upstream_connect_attempt_total 32547
telemt_upstream_connect_success_total 32483
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1434
telemt_me_reconnect_success_total 688
telemt_me_reader_eof_total 699
telemt_me_idle_close_by_peer_total 699
telemt_me_route_drop_no_conn_total 4429882
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5838257
telemt_me_endpoint_quarantine_total 568
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 673
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 24411
telemt_desync_full_logged_total 8074
telemt_desync_suppressed_total 16337
telemt_desync_frames_bucket_total{bucket="1_2"} 5199
telemt_desync_frames_bucket_total{bucket="3_10"} 9610
telemt_desync_frames_bucket_total{bucket="gt_10"} 9602
telemt_pool_swap_total 97
telemt_pool_force_close_total 3281
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 537
telemt_me_draining_writers_reap_progress_total 29668
telemt_me_writer_removed_unexpected_total 672
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2529
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27403
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3046
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 235
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26387
telemt_me_writer_teardown_success_total{mode="normal"} 29932
telemt_me_writer_teardown_noop_total 29708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59640
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 145.450027
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59640
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 537
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 614
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5831182
telemt_user_connections_current{user="hello"} 2560
telemt_user_octets_from_client{user="hello"} 100366854016 (93.47 GB)
telemt_user_octets_to_client{user="hello"} 1871181487124 (1.70 TB)
telemt_user_unique_ips_current{user="hello"} 1131
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 90586.8 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5833740
telemt_connections_bad_total 570014
telemt_connections_current 2374
telemt_connections_me_current 2374
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 190262
telemt_upstream_connect_attempt_total 36532
telemt_upstream_connect_success_total 36204
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 36373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17366
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1715
telemt_me_reconnect_success_total 720
telemt_me_reader_eof_total 696
telemt_me_idle_close_by_peer_total 696
telemt_me_route_drop_no_conn_total 2028557
telemt_me_route_drop_channel_closed_total 230
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4351316
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 691
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 20948
telemt_desync_full_logged_total 6982
telemt_desync_suppressed_total 13966
telemt_desync_frames_bucket_total{bucket="1_2"} 5082
telemt_desync_frames_bucket_total{bucket="3_10"} 8103
telemt_desync_frames_bucket_total{bucket="gt_10"} 7763
telemt_pool_swap_total 99
telemt_pool_force_close_total 3008
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 335
telemt_me_draining_writers_reap_progress_total 28288
telemt_me_writer_removed_unexpected_total 673
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2442
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26450
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2809
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25280
telemt_me_writer_teardown_success_total{mode="normal"} 28892
telemt_me_writer_teardown_noop_total 28293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57185
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.810013
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57185
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 335
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 619
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4330163
telemt_user_connections_current{user="hello"} 2374
telemt_user_octets_from_client{user="hello"} 133359063577 (124.20 GB)
telemt_user_octets_to_client{user="hello"} 2006166027611 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1011
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 90550.8 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5757466
telemt_connections_bad_total 527135
telemt_connections_current 2242
telemt_connections_me_current 2242
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 178147
telemt_upstream_connect_attempt_total 42954
telemt_upstream_connect_success_total 42675
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 42810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1752
telemt_me_reconnect_success_total 783
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 731
telemt_me_route_drop_no_conn_total 2049126
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4321661
telemt_me_endpoint_quarantine_total 605
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 676
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 20700
telemt_desync_full_logged_total 6800
telemt_desync_suppressed_total 13900
telemt_desync_frames_bucket_total{bucket="1_2"} 5143
telemt_desync_frames_bucket_total{bucket="3_10"} 7853
telemt_desync_frames_bucket_total{bucket="gt_10"} 7704
telemt_pool_swap_total 97
telemt_pool_force_close_total 2883
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 347
telemt_me_draining_writers_reap_progress_total 29708
telemt_me_writer_removed_unexpected_total 700
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2535
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27877
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2668
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26825
telemt_me_writer_teardown_success_total{mode="normal"} 30412
telemt_me_writer_teardown_noop_total 29718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60130
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.694334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60130
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 347
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 677
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 4323496
telemt_user_connections_current{user="hello"} 2242
telemt_user_octets_from_client{user="hello"} 127178849355 (118.44 GB)
telemt_user_octets_to_client{user="hello"} 1973243148479 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 955
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 90590.2 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19499482
telemt_connections_bad_total 1326593
telemt_connections_current 2911
telemt_connections_me_current 2911
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 549409
telemt_upstream_connect_attempt_total 182590
telemt_upstream_connect_success_total 165296
telemt_upstream_connect_fail_total 15817
telemt_upstream_connect_attempts_per_request{bucket="1"} 181113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8854
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15817
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59718
telemt_me_reconnect_success_total 1951
telemt_me_reader_eof_total 1282
telemt_me_idle_close_by_peer_total 1281
telemt_me_route_drop_no_conn_total 39364980
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15984542
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 659
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 704
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 30344
telemt_desync_full_logged_total 8963
telemt_desync_suppressed_total 21381
telemt_desync_frames_bucket_total{bucket="1_2"} 6647
telemt_desync_frames_bucket_total{bucket="3_10"} 13459
telemt_desync_frames_bucket_total{bucket="gt_10"} 10238
telemt_pool_swap_total 92
telemt_pool_force_close_total 3105
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 27914
telemt_me_writer_removed_unexpected_total 1832
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25677
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 507
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24809
telemt_me_writer_teardown_success_total{mode="normal"} 29490
telemt_me_writer_teardown_noop_total 27940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57430
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.874534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57430
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 3520
telemt_me_writer_restored_same_endpoint_total 1370
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 16109542
telemt_user_connections_current{user="hello"} 2911
telemt_user_octets_from_client{user="hello"} 164188951294 (152.91 GB)
telemt_user_octets_to_client{user="hello"} 1018582091874 (948.63 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1249
telemt_user_unique_ips_recent_window{user="hello"} 357
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 90557.6 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5604057
telemt_connections_bad_total 529009
telemt_connections_current 2130
telemt_connections_me_current 2130
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 115441
telemt_upstream_connect_attempt_total 46175
telemt_upstream_connect_success_total 45653
telemt_upstream_connect_fail_total 436
telemt_upstream_connect_attempts_per_request{bucket="1"} 46089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 436
telemt_me_reconnect_attempts_total 11237
telemt_me_reconnect_success_total 1310
telemt_me_reader_eof_total 1225
telemt_me_idle_close_by_peer_total 1225
telemt_me_route_drop_no_conn_total 2311167
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4360752
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 676
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 21835
telemt_desync_full_logged_total 7582
telemt_desync_suppressed_total 14253
telemt_desync_frames_bucket_total{bucket="1_2"} 4157
telemt_desync_frames_bucket_total{bucket="3_10"} 8475
telemt_desync_frames_bucket_total{bucket="gt_10"} 9203
telemt_pool_swap_total 92
telemt_pool_force_close_total 2729
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 344
telemt_me_draining_writers_reap_progress_total 30579
telemt_me_writer_removed_unexpected_total 1216
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28692
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2361
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27850
telemt_me_writer_teardown_success_total{mode="normal"} 31809
telemt_me_writer_teardown_noop_total 30580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62389
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.604464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62389
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 344
telemt_me_refill_failed_total 597
telemt_me_writer_restored_same_endpoint_total 1101
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 1516
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 4350108
telemt_user_connections_current{user="hello"} 2130
telemt_user_octets_from_client{user="hello"} 115819670889 (107.87 GB)
telemt_user_octets_to_client{user="hello"} 1768000824167 (1.61 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 964
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 27393.4 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3385511
telemt_connections_bad_total 122369
telemt_connections_current 2078
telemt_connections_me_current 2078
telemt_handshake_timeouts_total 1427345
telemt_upstream_connect_attempt_total 9103
telemt_upstream_connect_success_total 8988
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 9097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_reconnect_attempts_total 2291
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 228
telemt_me_idle_close_by_peer_total 228
telemt_me_route_drop_no_conn_total 955608
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1620901
telemt_me_endpoint_quarantine_total 133
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 204
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 63
telemt_desync_total 8973
telemt_desync_full_logged_total 3005
telemt_desync_suppressed_total 5968
telemt_desync_frames_bucket_total{bucket="1_2"} 1619
telemt_desync_frames_bucket_total{bucket="3_10"} 3432
telemt_desync_frames_bucket_total{bucket="gt_10"} 3922
telemt_pool_swap_total 29
telemt_pool_force_close_total 932
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 7932
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 732
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7460
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 820
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7000
telemt_me_writer_teardown_success_total{mode="normal"} 8192
telemt_me_writer_teardown_noop_total 7933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16125
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.468650
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16125
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 258
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 690
telemt_user_connections_total{user="hello"} 1616143
telemt_user_connections_current{user="hello"} 2078
telemt_user_octets_from_client{user="hello"} 46997586020 (43.77 GB)
telemt_user_octets_to_client{user="hello"} 690237151412 (642.83 GB)
telemt_user_unique_ips_current{user="hello"} 924
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 8364.4 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109868
telemt_connections_bad_total 1216
telemt_connections_current 513
telemt_connections_me_current 513
telemt_handshake_timeouts_total 3122
telemt_upstream_connect_attempt_total 3577
telemt_upstream_connect_success_total 3566
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 73
telemt_me_reconnect_success_total 42
telemt_me_reader_eof_total 42
telemt_me_idle_close_by_peer_total 42
telemt_me_route_drop_no_conn_total 30852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94463
telemt_me_endpoint_quarantine_total 61
telemt_me_single_endpoint_shadow_rotate_total 77
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 860
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 9
telemt_pool_force_close_total 240
telemt_me_writer_close_signal_drop_total 12
telemt_me_draining_writers_reap_progress_total 3138
telemt_me_writer_removed_unexpected_total 42
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 208
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2972
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2898
telemt_me_writer_teardown_success_total{mode="normal"} 3180
telemt_me_writer_teardown_noop_total 3138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6318
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.516090
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6318
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 12
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 94323
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 2119905216 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 60875679680 (56.69 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 90562.0 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6671448
telemt_connections_bad_total 673632
telemt_connections_current 2632
telemt_connections_me_current 2632
telemt_handshake_timeouts_total 192881
telemt_upstream_connect_attempt_total 34253
telemt_upstream_connect_success_total 34117
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 34216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_reconnect_attempts_total 1415
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 695
telemt_me_idle_close_by_peer_total 695
telemt_me_route_drop_no_conn_total 2043510
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5104622
telemt_me_endpoint_quarantine_total 602
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 689
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 19593
telemt_desync_full_logged_total 6535
telemt_desync_suppressed_total 13058
telemt_desync_frames_bucket_total{bucket="1_2"} 4774
telemt_desync_frames_bucket_total{bucket="3_10"} 7156
telemt_desync_frames_bucket_total{bucket="gt_10"} 7663
telemt_pool_swap_total 100
telemt_pool_force_close_total 2740
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30785
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2493
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28977
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2655
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28045
telemt_me_writer_teardown_success_total{mode="normal"} 31470
telemt_me_writer_teardown_noop_total 30787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62257
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.136054
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62257
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 5080251
telemt_user_connections_current{user="hello"} 2632
telemt_user_octets_from_client{user="hello"} 102055332780 (95.05 GB)
telemt_user_octets_to_client{user="hello"} 2381008283588 (2.17 TB)
telemt_user_unique_ips_current{user="hello"} 1063
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 90558.8 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5684838
telemt_connections_bad_total 538800
telemt_connections_current 2731
telemt_connections_me_current 2731
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 161683
telemt_upstream_connect_attempt_total 50450
telemt_upstream_connect_success_total 50076
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 50391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_reconnect_attempts_total 4586
telemt_me_reconnect_success_total 1007
telemt_me_reader_eof_total 896
telemt_me_idle_close_by_peer_total 896
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2099012
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4472572
telemt_me_endpoint_quarantine_total 709
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 688
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 18173
telemt_desync_full_logged_total 6143
telemt_desync_suppressed_total 12030
telemt_desync_frames_bucket_total{bucket="1_2"} 4480
telemt_desync_frames_bucket_total{bucket="3_10"} 6660
telemt_desync_frames_bucket_total{bucket="gt_10"} 7033
telemt_pool_swap_total 98
telemt_pool_force_close_total 2682
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 29807
telemt_me_writer_removed_unexpected_total 907
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2978
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27778
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 208
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27125
telemt_me_writer_teardown_success_total{mode="normal"} 30756
telemt_me_writer_teardown_noop_total 29811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60567
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.157684
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60567
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 204
telemt_me_writer_restored_same_endpoint_total 776
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 4476287
telemt_user_connections_current{user="hello"} 2731
telemt_user_octets_from_client{user="hello"} 85257042177 (79.40 GB)
telemt_user_octets_to_client{user="hello"} 1907381589912 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1091
telemt_user_unique_ips_recent_window{user="hello"} 296
```