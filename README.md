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

# Server Metrics 2026-03-22 07:01:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 35711.1 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710761
telemt_connections_bad_total 43842
telemt_connections_current 1550
telemt_connections_me_current 1550
telemt_handshake_timeouts_total 34200
telemt_upstream_connect_attempt_total 14551
telemt_upstream_connect_success_total 14550
telemt_upstream_connect_attempts_per_request{bucket="1"} 14550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 381
telemt_me_reconnect_success_total 230
telemt_me_reader_eof_total 226
telemt_me_idle_close_by_peer_total 226
telemt_me_route_drop_no_conn_total 252902
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589400
telemt_me_endpoint_quarantine_total 262
telemt_me_single_endpoint_shadow_rotate_total 294
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 4827
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 3471
telemt_desync_frames_bucket_total{bucket="1_2"} 1574
telemt_desync_frames_bucket_total{bucket="3_10"} 1801
telemt_desync_frames_bucket_total{bucket="gt_10"} 1452
telemt_pool_swap_total 39
telemt_pool_force_close_total 1048
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 13167
telemt_me_writer_removed_unexpected_total 223
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 914
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12463
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1037
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12119
telemt_me_writer_teardown_success_total{mode="normal"} 13377
telemt_me_writer_teardown_noop_total 13168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26545
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.760791
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26545
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 588245
telemt_user_connections_current{user="hello"} 1550
telemt_user_octets_from_client{user="hello"} 8247419336 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 205474722484 (191.36 GB)
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 49077.2 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193961
telemt_connections_bad_total 118608
telemt_connections_current 1450
telemt_connections_me_current 1450
telemt_handshake_timeouts_total 37633
telemt_upstream_connect_attempt_total 25978
telemt_upstream_connect_success_total 25595
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 25927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1927
telemt_me_reconnect_success_total 764
telemt_me_reader_eof_total 669
telemt_me_idle_close_by_peer_total 669
telemt_me_route_drop_no_conn_total 437475
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 898868
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 395
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 3823
telemt_desync_full_logged_total 2239
telemt_desync_suppressed_total 1584
telemt_desync_frames_bucket_total{bucket="1_2"} 804
telemt_desync_frames_bucket_total{bucket="3_10"} 1481
telemt_desync_frames_bucket_total{bucket="gt_10"} 1538
telemt_pool_swap_total 52
telemt_pool_force_close_total 1389
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 20217
telemt_me_writer_removed_unexpected_total 643
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1786
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19059
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1323
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18828
telemt_me_writer_teardown_success_total{mode="normal"} 20845
telemt_me_writer_teardown_noop_total 20217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41062
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.277942
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41062
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 900641
telemt_user_connections_current{user="hello"} 1450
telemt_user_octets_from_client{user="hello"} 14462068966 (13.47 GB)
telemt_user_octets_to_client{user="hello"} 334726724115 (311.74 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 874
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 123937.3 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8864136
telemt_connections_bad_total 820863
telemt_connections_current 4505
telemt_connections_me_current 4505
telemt_handshake_timeouts_total 278858
telemt_upstream_connect_attempt_total 45862
telemt_upstream_connect_success_total 45784
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1748
telemt_me_reconnect_success_total 911
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 913
telemt_me_route_drop_no_conn_total 4820819
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6996236
telemt_me_endpoint_quarantine_total 788
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 932
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 30095
telemt_desync_full_logged_total 9971
telemt_desync_suppressed_total 20124
telemt_desync_frames_bucket_total{bucket="1_2"} 6531
telemt_desync_frames_bucket_total{bucket="3_10"} 11725
telemt_desync_frames_bucket_total{bucket="gt_10"} 11839
telemt_pool_swap_total 134
telemt_pool_force_close_total 4425
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 41868
telemt_me_writer_removed_unexpected_total 878
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38769
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4160
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37443
telemt_me_writer_teardown_success_total{mode="normal"} 42245
telemt_me_writer_teardown_noop_total 41912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84157
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 176.422891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84157
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 812
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 6987104
telemt_user_connections_current{user="hello"} 4505
telemt_user_octets_from_client{user="hello"} 118198822040 (110.08 GB)
telemt_user_octets_to_client{user="hello"} 2391356491948 (2.17 TB)
telemt_user_unique_ips_current{user="hello"} 1765
telemt_user_unique_ips_recent_window{user="hello"} 747
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 123938.8 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7302066
telemt_connections_bad_total 643941
telemt_connections_current 4366
telemt_connections_me_current 4366
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 240953
telemt_upstream_connect_attempt_total 49869
telemt_upstream_connect_success_total 49463
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2623
telemt_me_reconnect_success_total 982
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 2456654
telemt_me_route_drop_channel_closed_total 301
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5408085
telemt_me_endpoint_quarantine_total 786
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 954
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 24896
telemt_desync_full_logged_total 8561
telemt_desync_suppressed_total 16335
telemt_desync_frames_bucket_total{bucket="1_2"} 5957
telemt_desync_frames_bucket_total{bucket="3_10"} 9670
telemt_desync_frames_bucket_total{bucket="gt_10"} 9269
telemt_pool_swap_total 135
telemt_pool_force_close_total 4026
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 417
telemt_me_draining_writers_reap_progress_total 40330
telemt_me_writer_removed_unexpected_total 925
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3339
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37845
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3793
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36304
telemt_me_writer_teardown_success_total{mode="normal"} 41184
telemt_me_writer_teardown_noop_total 40336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81520
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.871368
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81520
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 417
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 858
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 5329201
telemt_user_connections_current{user="hello"} 4366
telemt_user_octets_from_client{user="hello"} 152061239233 (141.62 GB)
telemt_user_octets_to_client{user="hello"} 2579199339443 (2.35 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1696
telemt_user_unique_ips_recent_window{user="hello"} 674
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 123912.7 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7044232
telemt_connections_bad_total 586298
telemt_connections_current 3856
telemt_connections_me_current 3856
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 235806
telemt_upstream_connect_attempt_total 56324
telemt_upstream_connect_success_total 55695
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 55840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26023
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2655
telemt_me_reconnect_success_total 1130
telemt_me_reader_eof_total 1053
telemt_me_idle_close_by_peer_total 1053
telemt_me_route_drop_no_conn_total 2578251
telemt_me_route_drop_channel_closed_total 162
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5246274
telemt_me_endpoint_quarantine_total 877
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 919
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 24798
telemt_desync_full_logged_total 8419
telemt_desync_suppressed_total 16379
telemt_desync_frames_bucket_total{bucket="1_2"} 6009
telemt_desync_frames_bucket_total{bucket="3_10"} 9504
telemt_desync_frames_bucket_total{bucket="gt_10"} 9285
telemt_pool_swap_total 133
telemt_pool_force_close_total 3895
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 435
telemt_me_draining_writers_reap_progress_total 41235
telemt_me_writer_removed_unexpected_total 1044
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3602
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38691
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37340
telemt_me_writer_teardown_success_total{mode="normal"} 42293
telemt_me_writer_teardown_noop_total 41247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83540
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.515778
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83540
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 435
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 974
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 5240073
telemt_user_connections_current{user="hello"} 3856
telemt_user_octets_from_client{user="hello"} 141354116103 (131.65 GB)
telemt_user_octets_to_client{user="hello"} 2371540489031 (2.16 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1453
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 123942.1 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22581857
telemt_connections_bad_total 1902286
telemt_connections_current 5823
telemt_connections_me_current 5823
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 674167
telemt_upstream_connect_attempt_total 238628
telemt_upstream_connect_success_total 219004
telemt_upstream_connect_fail_total 17675
telemt_upstream_connect_attempts_per_request{bucket="1"} 236679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17675
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66394
telemt_me_reconnect_success_total 2622
telemt_me_reader_eof_total 1650
telemt_me_idle_close_by_peer_total 1648
telemt_me_route_drop_no_conn_total 42785324
telemt_me_route_drop_channel_closed_total 135
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18164564
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 967
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 971
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 35054
telemt_desync_full_logged_total 10538
telemt_desync_suppressed_total 24516
telemt_desync_frames_bucket_total{bucket="1_2"} 7803
telemt_desync_frames_bucket_total{bucket="3_10"} 15455
telemt_desync_frames_bucket_total{bucket="gt_10"} 11796
telemt_pool_swap_total 128
telemt_pool_force_close_total 4057
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 927
telemt_me_draining_writers_reap_progress_total 38795
telemt_me_writer_removed_unexpected_total 2428
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5248
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35706
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3478
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 579
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34738
telemt_me_writer_teardown_success_total{mode="normal"} 40954
telemt_me_writer_teardown_noop_total 38825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79779
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 279.580831
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79779
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 927
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1785
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 18329311
telemt_user_connections_current{user="hello"} 5823
telemt_user_octets_from_client{user="hello"} 269003075447 (250.53 GB)
telemt_user_octets_to_client{user="hello"} 1391906952566 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 500908
telemt_user_msgs_to_client{user="hello"} 1006528
telemt_user_unique_ips_current{user="hello"} 2081
telemt_user_unique_ips_recent_window{user="hello"} 1233
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 123909.4 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6763214
telemt_connections_bad_total 624309
telemt_connections_current 3925
telemt_connections_me_current 3925
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 140182
telemt_upstream_connect_attempt_total 64931
telemt_upstream_connect_success_total 64189
telemt_upstream_connect_fail_total 636
telemt_upstream_connect_attempts_per_request{bucket="1"} 64825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 636
telemt_me_reconnect_attempts_total 70001
telemt_me_reconnect_success_total 1918
telemt_me_reader_eof_total 1696
telemt_me_idle_close_by_peer_total 1695
telemt_me_route_drop_no_conn_total 2588379
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5285575
telemt_me_endpoint_quarantine_total 830
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 941
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 26496
telemt_desync_full_logged_total 9218
telemt_desync_suppressed_total 17278
telemt_desync_frames_bucket_total{bucket="1_2"} 5307
telemt_desync_frames_bucket_total{bucket="3_10"} 10171
telemt_desync_frames_bucket_total{bucket="gt_10"} 11018
telemt_pool_swap_total 129
telemt_pool_force_close_total 3700
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 435
telemt_me_draining_writers_reap_progress_total 43493
telemt_me_writer_removed_unexpected_total 1727
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4358
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40899
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3290
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 410
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39793
telemt_me_writer_teardown_success_total{mode="normal"} 45257
telemt_me_writer_teardown_noop_total 43494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88751
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.918602
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88751
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 435
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1602
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5276974
telemt_user_connections_current{user="hello"} 3925
telemt_user_octets_from_client{user="hello"} 135442073620 (126.14 GB)
telemt_user_octets_to_client{user="hello"} 2209157120338 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1651
telemt_user_unique_ips_recent_window{user="hello"} 626
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 60745.5 (16h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4959016
telemt_connections_bad_total 201401
telemt_connections_current 3727
telemt_connections_me_current 3727
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1962253
telemt_upstream_connect_attempt_total 33779
telemt_upstream_connect_success_total 33548
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 33772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_reconnect_attempts_total 46193
telemt_me_reconnect_success_total 1071
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 1215942
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2471464
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 469
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 13189
telemt_desync_full_logged_total 4551
telemt_desync_suppressed_total 8638
telemt_desync_frames_bucket_total{bucket="1_2"} 2599
telemt_desync_frames_bucket_total{bucket="3_10"} 5031
telemt_desync_frames_bucket_total{bucket="gt_10"} 5559
telemt_pool_swap_total 66
telemt_pool_force_close_total 1941
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 169
telemt_me_draining_writers_reap_progress_total 22205
telemt_me_writer_removed_unexpected_total 831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1872
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21186
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1718
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20264
telemt_me_writer_teardown_success_total{mode="normal"} 23058
telemt_me_writer_teardown_noop_total 22207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45265
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.867424
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45265
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 169
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2473248
telemt_user_connections_current{user="hello"} 3727
telemt_user_octets_from_client{user="hello"} 64043173956 (59.64 GB)
telemt_user_octets_to_client{user="hello"} 1098355036158 (1022.92 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1520
telemt_user_unique_ips_recent_window{user="hello"} 652
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 41716.0 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317240
telemt_connections_bad_total 2159
telemt_connections_current 841
telemt_connections_me_current 841
telemt_handshake_timeouts_total 7319
telemt_upstream_connect_attempt_total 20045
telemt_upstream_connect_success_total 19992
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 20040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 838
telemt_me_reconnect_success_total 289
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 93940
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286909
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 364
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
telemt_me_writers_active_current 46
telemt_desync_total 1383
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 994
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 46
telemt_pool_force_close_total 1032
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 18146
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1186
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17245
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1030
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17114
telemt_me_writer_teardown_success_total{mode="normal"} 18431
telemt_me_writer_teardown_noop_total 18146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36577
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.475618
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36577
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 248
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 286479
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 4762415216 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 163167586968 (151.96 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 123914.3 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8235987
telemt_connections_bad_total 864680
telemt_connections_current 4592
telemt_connections_me_current 4592
telemt_handshake_timeouts_total 232185
telemt_upstream_connect_attempt_total 48636
telemt_upstream_connect_success_total 48456
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 48597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_reconnect_attempts_total 1790
telemt_me_reconnect_success_total 965
telemt_me_reader_eof_total 947
telemt_me_idle_close_by_peer_total 947
telemt_me_route_drop_no_conn_total 2318035
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6134618
telemt_me_endpoint_quarantine_total 881
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 947
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
telemt_desync_total 24377
telemt_desync_full_logged_total 8017
telemt_desync_suppressed_total 16360
telemt_desync_frames_bucket_total{bucket="1_2"} 6055
telemt_desync_frames_bucket_total{bucket="3_10"} 8898
telemt_desync_frames_bucket_total{bucket="gt_10"} 9424
telemt_pool_swap_total 137
telemt_pool_force_close_total 3658
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 436
telemt_me_draining_writers_reap_progress_total 43919
telemt_me_writer_removed_unexpected_total 910
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3445
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41411
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3566
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40261
telemt_me_writer_teardown_success_total{mode="normal"} 44856
telemt_me_writer_teardown_noop_total 43921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88777
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.362575
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88777
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 436
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 855
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6108568
telemt_user_connections_current{user="hello"} 4592
telemt_user_octets_from_client{user="hello"} 120201026964 (111.95 GB)
telemt_user_octets_to_client{user="hello"} 2863159089760 (2.60 TB)
telemt_user_unique_ips_current{user="hello"} 1723
telemt_user_unique_ips_recent_window{user="hello"} 734
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 123910.7 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7201227
telemt_connections_bad_total 748347
telemt_connections_current 3965
telemt_connections_me_current 3965
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 192304
telemt_upstream_connect_attempt_total 64407
telemt_upstream_connect_success_total 63916
telemt_upstream_connect_fail_total 428
telemt_upstream_connect_attempts_per_request{bucket="1"} 64344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 428
telemt_me_reconnect_attempts_total 5916
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 1194
telemt_me_idle_close_by_peer_total 1194
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2379324
telemt_me_route_drop_channel_closed_total 198
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5493375
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 947
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_active_current 42
telemt_desync_total 23298
telemt_desync_full_logged_total 7737
telemt_desync_suppressed_total 15561
telemt_desync_frames_bucket_total{bucket="1_2"} 5767
telemt_desync_frames_bucket_total{bucket="3_10"} 8558
telemt_desync_frames_bucket_total{bucket="gt_10"} 8973
telemt_pool_swap_total 135
telemt_pool_force_close_total 3610
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 436
telemt_me_draining_writers_reap_progress_total 42391
telemt_me_writer_removed_unexpected_total 1209
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4002
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39659
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 232
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38781
telemt_me_writer_teardown_success_total{mode="normal"} 43661
telemt_me_writer_teardown_noop_total 42395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86056
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.442887
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86056
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 436
telemt_me_refill_failed_total 264
telemt_me_writer_restored_same_endpoint_total 1033
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 5495226
telemt_user_connections_current{user="hello"} 3965
telemt_user_octets_from_client{user="hello"} 101973019369 (94.97 GB)
telemt_user_octets_to_client{user="hello"} 2387204782180 (2.17 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1621
telemt_user_unique_ips_recent_window{user="hello"} 700
```