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

# Server Metrics 2026-03-21 22:31:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 5106.7 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93461
telemt_connections_bad_total 6645
telemt_connections_current 758
telemt_connections_me_current 758
telemt_handshake_timeouts_total 4356
telemt_upstream_connect_attempt_total 2009
telemt_upstream_connect_success_total 2008
telemt_upstream_connect_attempts_per_request{bucket="1"} 2008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 43
telemt_me_reconnect_success_total 25
telemt_me_reader_eof_total 26
telemt_me_idle_close_by_peer_total 26
telemt_me_route_drop_no_conn_total 19297
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76096
telemt_me_endpoint_quarantine_total 31
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 521
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 5
telemt_pool_force_close_total 134
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 1759
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1661
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1625
telemt_me_writer_teardown_success_total{mode="normal"} 1785
telemt_me_writer_teardown_noop_total 1759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3544
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.130902
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3544
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 76026
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 1041914064 (993.65 MB)
telemt_user_octets_to_client{user="hello"} 28535451756 (26.58 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 18472.9 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606116
telemt_connections_bad_total 27920
telemt_connections_current 501
telemt_connections_me_current 501
telemt_handshake_timeouts_total 22029
telemt_upstream_connect_attempt_total 7523
telemt_upstream_connect_success_total 7385
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 7508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_reconnect_attempts_total 622
telemt_me_reconnect_success_total 224
telemt_me_reader_eof_total 192
telemt_me_idle_close_by_peer_total 192
telemt_me_route_drop_no_conn_total 312995
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 493473
telemt_me_endpoint_quarantine_total 152
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 2203
telemt_desync_full_logged_total 1250
telemt_desync_suppressed_total 953
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 840
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 20
telemt_pool_force_close_total 579
telemt_me_writer_close_signal_drop_total 44
telemt_me_draining_writers_reap_progress_total 6612
telemt_me_writer_removed_unexpected_total 181
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 579
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6212
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 572
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6033
telemt_me_writer_teardown_success_total{mode="normal"} 6791
telemt_me_writer_teardown_noop_total 6612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13403
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.111366
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13403
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 44
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 155
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 492820
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 8477833160 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 168473083480 (156.90 GB)
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 93332.9 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7252592
telemt_connections_bad_total 554626
telemt_connections_current 2034
telemt_connections_me_current 2034
telemt_handshake_timeouts_total 228229
telemt_upstream_connect_attempt_total 33586
telemt_upstream_connect_success_total 33518
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 33525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1460
telemt_me_reconnect_success_total 714
telemt_me_reader_eof_total 723
telemt_me_idle_close_by_peer_total 723
telemt_me_route_drop_no_conn_total 4464843
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5937996
telemt_me_endpoint_quarantine_total 587
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 690
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_me_writers_active_current 46
telemt_desync_total 25105
telemt_desync_full_logged_total 8260
telemt_desync_suppressed_total 16845
telemt_desync_frames_bucket_total{bucket="1_2"} 5398
telemt_desync_frames_bucket_total{bucket="3_10"} 9822
telemt_desync_frames_bucket_total{bucket="gt_10"} 9885
telemt_pool_swap_total 100
telemt_pool_force_close_total 3390
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 554
telemt_me_draining_writers_reap_progress_total 30583
telemt_me_writer_removed_unexpected_total 695
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2614
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27193
telemt_me_writer_teardown_success_total{mode="normal"} 30855
telemt_me_writer_teardown_noop_total 30627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61482
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 150.490185
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61482
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 554
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5930744
telemt_user_connections_current{user="hello"} 2034
telemt_user_octets_from_client{user="hello"} 101813851880 (94.82 GB)
telemt_user_octets_to_client{user="hello"} 1922827866732 (1.75 TB)
telemt_user_unique_ips_current{user="hello"} 954
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 93334.1 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5955253
telemt_connections_bad_total 573609
telemt_connections_current 1870
telemt_connections_me_current 1870
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 194952
telemt_upstream_connect_attempt_total 37563
telemt_upstream_connect_success_total 37229
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 37403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17903
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1738
telemt_me_reconnect_success_total 741
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 2093833
telemt_me_route_drop_channel_closed_total 242
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4452028
telemt_me_endpoint_quarantine_total 566
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 713
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
telemt_desync_total 21451
telemt_desync_full_logged_total 7178
telemt_desync_suppressed_total 14273
telemt_desync_frames_bucket_total{bucket="1_2"} 5191
telemt_desync_frames_bucket_total{bucket="3_10"} 8293
telemt_desync_frames_bucket_total{bucket="gt_10"} 7967
telemt_pool_swap_total 102
telemt_pool_force_close_total 3092
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 29197
telemt_me_writer_removed_unexpected_total 693
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2510
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27312
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26105
telemt_me_writer_teardown_success_total{mode="normal"} 29822
telemt_me_writer_teardown_noop_total 29203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59025
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.134533
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59025
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 639
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4415498
telemt_user_connections_current{user="hello"} 1870
telemt_user_octets_from_client{user="hello"} 136486423329 (127.11 GB)
telemt_user_octets_to_client{user="hello"} 2057411479843 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 862
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 93297.9 (25h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5876093
telemt_connections_bad_total 532790
telemt_connections_current 1803
telemt_connections_me_current 1803
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 184696
telemt_upstream_connect_attempt_total 43938
telemt_upstream_connect_success_total 43641
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 43776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1781
telemt_me_reconnect_success_total 797
telemt_me_reader_eof_total 743
telemt_me_idle_close_by_peer_total 743
telemt_me_route_drop_no_conn_total 2072940
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4398700
telemt_me_endpoint_quarantine_total 624
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 695
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 21266
telemt_desync_full_logged_total 6987
telemt_desync_suppressed_total 14279
telemt_desync_frames_bucket_total{bucket="1_2"} 5250
telemt_desync_frames_bucket_total{bucket="3_10"} 8068
telemt_desync_frames_bucket_total{bucket="gt_10"} 7948
telemt_pool_swap_total 100
telemt_pool_force_close_total 2969
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 30599
telemt_me_writer_removed_unexpected_total 712
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2589
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28727
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2754
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27630
telemt_me_writer_teardown_success_total{mode="normal"} 31316
telemt_me_writer_teardown_noop_total 30610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61926
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.993771
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61926
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 690
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 4400347
telemt_user_connections_current{user="hello"} 1803
telemt_user_octets_from_client{user="hello"} 129580421291 (120.68 GB)
telemt_user_octets_to_client{user="hello"} 2012453725507 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 886
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 93337.4 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19678476
telemt_connections_bad_total 1381530
telemt_connections_current 2636
telemt_connections_me_current 2636
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 560382
telemt_upstream_connect_attempt_total 183633
telemt_upstream_connect_success_total 166308
telemt_upstream_connect_fail_total 15823
telemt_upstream_connect_attempts_per_request{bucket="1"} 182131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38150
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8858
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15823
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 60240
telemt_me_reconnect_success_total 1987
telemt_me_reader_eof_total 1289
telemt_me_idle_close_by_peer_total 1288
telemt_me_route_drop_no_conn_total 39405266
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16092270
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 690
telemt_me_single_endpoint_outage_enter_total 112
telemt_me_single_endpoint_outage_exit_total 112
telemt_me_single_endpoint_outage_reconnect_attempt_total 240
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 240
telemt_me_single_endpoint_shadow_rotate_total 725
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
telemt_me_writers_active_current 49
telemt_desync_total 30833
telemt_desync_full_logged_total 9127
telemt_desync_suppressed_total 21706
telemt_desync_frames_bucket_total{bucket="1_2"} 6752
telemt_desync_frames_bucket_total{bucket="3_10"} 13668
telemt_desync_frames_bucket_total{bucket="gt_10"} 10413
telemt_pool_swap_total 95
telemt_pool_force_close_total 3202
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 723
telemt_me_draining_writers_reap_progress_total 28846
telemt_me_writer_removed_unexpected_total 1862
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3918
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26517
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2694
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 508
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25644
telemt_me_writer_teardown_success_total{mode="normal"} 30435
telemt_me_writer_teardown_noop_total 28872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59307
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.550433
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59307
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 723
telemt_me_refill_failed_total 3549
telemt_me_writer_restored_same_endpoint_total 1397
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14284
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 16217175
telemt_user_connections_current{user="hello"} 2636
telemt_user_octets_from_client{user="hello"} 171808237258 (160.01 GB)
telemt_user_octets_to_client{user="hello"} 1058145991310 (985.48 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1151
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 93304.8 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5699829
telemt_connections_bad_total 534473
telemt_connections_current 1950
telemt_connections_me_current 1950
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 117994
telemt_upstream_connect_attempt_total 51383
telemt_upstream_connect_success_total 50833
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 51297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_reconnect_attempts_total 11764
telemt_me_reconnect_success_total 1341
telemt_me_reader_eof_total 1245
telemt_me_idle_close_by_peer_total 1245
telemt_me_route_drop_no_conn_total 2331721
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4439363
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 697
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22347
telemt_desync_full_logged_total 7775
telemt_desync_suppressed_total 14572
telemt_desync_frames_bucket_total{bucket="1_2"} 4259
telemt_desync_frames_bucket_total{bucket="3_10"} 8671
telemt_desync_frames_bucket_total{bucket="gt_10"} 9417
telemt_pool_swap_total 95
telemt_pool_force_close_total 2785
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 31563
telemt_me_writer_removed_unexpected_total 1246
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3218
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29605
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2417
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28778
telemt_me_writer_teardown_success_total{mode="normal"} 32823
telemt_me_writer_teardown_noop_total 31564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64387
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.641014
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64387
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 625
telemt_me_writer_restored_same_endpoint_total 1118
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 1544
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 4432490
telemt_user_connections_current{user="hello"} 1950
telemt_user_octets_from_client{user="hello"} 117505813528 (109.44 GB)
telemt_user_octets_to_client{user="hello"} 1803748746638 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 926
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 30140.6 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3537321
telemt_connections_bad_total 125143
telemt_connections_current 1759
telemt_connections_me_current 1759
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1491760
telemt_upstream_connect_attempt_total 15425
telemt_upstream_connect_success_total 15300
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 15419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 22080
telemt_me_reconnect_success_total 540
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 973840
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1691559
telemt_me_endpoint_quarantine_total 183
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 225
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_floor_cap_block_total 13
telemt_me_floor_swap_idle_failed_total 13
telemt_desync_total 9333
telemt_desync_full_logged_total 3147
telemt_desync_suppressed_total 6186
telemt_desync_frames_bucket_total{bucket="1_2"} 1659
telemt_desync_frames_bucket_total{bucket="3_10"} 3583
telemt_desync_frames_bucket_total{bucket="gt_10"} 4091
telemt_pool_swap_total 32
telemt_pool_force_close_total 1053
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 9137
telemt_me_writer_removed_unexpected_total 409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 947
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8613
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8084
telemt_me_writer_teardown_success_total{mode="normal"} 9560
telemt_me_writer_teardown_noop_total 9138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18698
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.730373
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18698
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 1212
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 160
telemt_me_async_recovery_trigger_total 2130
telemt_user_connections_total{user="hello"} 1691706
telemt_user_connections_current{user="hello"} 1759
telemt_user_octets_from_client{user="hello"} 48974682024 (45.61 GB)
telemt_user_octets_to_client{user="hello"} 726263193466 (676.39 GB)
telemt_user_msgs_from_client{user="hello"} 43112
telemt_user_msgs_to_client{user="hello"} 113951
telemt_user_unique_ips_current{user="hello"} 825
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 11111.6 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131236
telemt_connections_bad_total 1324
telemt_connections_current 504
telemt_connections_me_current 504
telemt_handshake_timeouts_total 3311
telemt_upstream_connect_attempt_total 4871
telemt_upstream_connect_success_total 4856
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 106
telemt_me_reconnect_success_total 57
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 37306
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113805
telemt_me_endpoint_quarantine_total 91
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 45
telemt_desync_total 920
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 694
telemt_desync_frames_bucket_total{bucket="1_2"} 376
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 12
telemt_pool_force_close_total 299
telemt_me_writer_close_signal_drop_total 15
telemt_me_draining_writers_reap_progress_total 4295
telemt_me_writer_removed_unexpected_total 59
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 279
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4077
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 297
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3996
telemt_me_writer_teardown_success_total{mode="normal"} 4356
telemt_me_writer_teardown_noop_total 4295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8651
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.608624
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8651
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 15
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 113638
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 2246937304 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 68311821408 (63.62 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 93309.3 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6811106
telemt_connections_bad_total 687253
telemt_connections_current 2269
telemt_connections_me_current 2269
telemt_handshake_timeouts_total 194684
telemt_upstream_connect_attempt_total 35331
telemt_upstream_connect_success_total 35190
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 35294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_reconnect_attempts_total 1437
telemt_me_reconnect_success_total 740
telemt_me_reader_eof_total 717
telemt_me_idle_close_by_peer_total 717
telemt_me_route_drop_no_conn_total 2068162
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5192404
telemt_me_endpoint_quarantine_total 621
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 713
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
telemt_me_writers_active_current 47
telemt_desync_total 19930
telemt_desync_full_logged_total 6656
telemt_desync_suppressed_total 13274
telemt_desync_frames_bucket_total{bucket="1_2"} 4853
telemt_desync_frames_bucket_total{bucket="3_10"} 7262
telemt_desync_frames_bucket_total{bucket="gt_10"} 7815
telemt_pool_swap_total 103
telemt_pool_force_close_total 2824
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 31743
telemt_me_writer_removed_unexpected_total 696
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2578
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29872
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2736
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28919
telemt_me_writer_teardown_success_total{mode="normal"} 32450
telemt_me_writer_teardown_noop_total 31745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64195
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.291564
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64195
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 662
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 5167819
telemt_user_connections_current{user="hello"} 2269
telemt_user_octets_from_client{user="hello"} 104232336288 (97.07 GB)
telemt_user_octets_to_client{user="hello"} 2429093717056 (2.21 TB)
telemt_user_unique_ips_current{user="hello"} 997
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 93305.7 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5804153
telemt_connections_bad_total 551655
telemt_connections_current 2038
telemt_connections_me_current 2038
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 163506
telemt_upstream_connect_attempt_total 51467
telemt_upstream_connect_success_total 51077
telemt_upstream_connect_fail_total 331
telemt_upstream_connect_attempts_per_request{bucket="1"} 51408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 331
telemt_me_reconnect_attempts_total 5223
telemt_me_reconnect_success_total 1047
telemt_me_reader_eof_total 924
telemt_me_idle_close_by_peer_total 924
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2120623
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4559280
telemt_me_endpoint_quarantine_total 726
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 709
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
telemt_me_writers_active_current 43
telemt_desync_total 18591
telemt_desync_full_logged_total 6282
telemt_desync_suppressed_total 12309
telemt_desync_frames_bucket_total{bucket="1_2"} 4626
telemt_desync_frames_bucket_total{bucket="3_10"} 6775
telemt_desync_frames_bucket_total{bucket="gt_10"} 7190
telemt_pool_swap_total 101
telemt_pool_force_close_total 2779
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 30692
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3075
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28594
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2556
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27913
telemt_me_writer_teardown_success_total{mode="normal"} 31669
telemt_me_writer_teardown_noop_total 30696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62365
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.488166
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62365
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 810
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4562823
telemt_user_connections_current{user="hello"} 2038
telemt_user_octets_from_client{user="hello"} 87472777365 (81.47 GB)
telemt_user_octets_to_client{user="hello"} 1957552715356 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 867
telemt_user_unique_ips_recent_window{user="hello"} 204
```