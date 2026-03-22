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

# Server Metrics 2026-03-22 05:04:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 28663.8 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478820
telemt_connections_bad_total 32365
telemt_connections_current 1305
telemt_connections_me_current 1305
telemt_handshake_timeouts_total 26432
telemt_upstream_connect_attempt_total 11867
telemt_upstream_connect_success_total 11866
telemt_upstream_connect_attempts_per_request{bucket="1"} 11866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 314
telemt_me_reconnect_success_total 184
telemt_me_reader_eof_total 180
telemt_me_idle_close_by_peer_total 180
telemt_me_route_drop_no_conn_total 100105
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394984
telemt_me_endpoint_quarantine_total 223
telemt_me_single_endpoint_shadow_rotate_total 237
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 3544
telemt_desync_full_logged_total 964
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1203
telemt_desync_frames_bucket_total{bucket="3_10"} 1364
telemt_desync_frames_bucket_total{bucket="gt_10"} 977
telemt_pool_swap_total 31
telemt_pool_force_close_total 815
telemt_me_writer_close_signal_drop_total 68
telemt_me_draining_writers_reap_progress_total 10733
telemt_me_writer_removed_unexpected_total 178
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 728
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 810
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9918
telemt_me_writer_teardown_success_total{mode="normal"} 10903
telemt_me_writer_teardown_noop_total 10734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21637
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.547812
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21637
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 68
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 167
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 394037
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 5409598736 (5.04 GB)
telemt_user_octets_to_client{user="hello"} 138866235056 (129.33 GB)
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 42030.2 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931577
telemt_connections_bad_total 65887
telemt_connections_current 994
telemt_connections_me_current 994
telemt_handshake_timeouts_total 32112
telemt_upstream_connect_attempt_total 22621
telemt_upstream_connect_success_total 22306
telemt_upstream_connect_fail_total 284
telemt_upstream_connect_attempts_per_request{bucket="1"} 22590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 284
telemt_me_reconnect_attempts_total 1670
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 543
telemt_me_idle_close_by_peer_total 543
telemt_me_route_drop_no_conn_total 366932
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 731275
telemt_me_endpoint_quarantine_total 400
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 342
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
telemt_me_writers_active_current 45
telemt_desync_total 3157
telemt_desync_full_logged_total 1819
telemt_desync_suppressed_total 1338
telemt_desync_frames_bucket_total{bucket="1_2"} 665
telemt_desync_frames_bucket_total{bucket="3_10"} 1211
telemt_desync_frames_bucket_total{bucket="gt_10"} 1281
telemt_pool_swap_total 45
telemt_pool_force_close_total 1178
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 17448
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1489
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16489
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16270
telemt_me_writer_teardown_success_total{mode="normal"} 17978
telemt_me_writer_teardown_noop_total 17448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35426
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.082323
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35426
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 466
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 733025
telemt_user_connections_current{user="hello"} 994
telemt_user_octets_from_client{user="hello"} 11701369667 (10.90 GB)
telemt_user_octets_to_client{user="hello"} 265486018954 (247.25 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 628
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 116889.9 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8147220
telemt_connections_bad_total 701169
telemt_connections_current 3237
telemt_connections_me_current 3237
telemt_handshake_timeouts_total 266379
telemt_upstream_connect_attempt_total 43577
telemt_upstream_connect_success_total 43499
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1642
telemt_me_reconnect_success_total 858
telemt_me_reader_eof_total 866
telemt_me_idle_close_by_peer_total 866
telemt_me_route_drop_no_conn_total 4608826
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6550270
telemt_me_endpoint_quarantine_total 746
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 878
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
telemt_me_writers_active_current 47
telemt_desync_total 27571
telemt_desync_full_logged_total 9181
telemt_desync_suppressed_total 18390
telemt_desync_frames_bucket_total{bucket="1_2"} 5954
telemt_desync_frames_bucket_total{bucket="3_10"} 10790
telemt_desync_frames_bucket_total{bucket="gt_10"} 10827
telemt_pool_swap_total 126
telemt_pool_force_close_total 4140
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 623
telemt_me_draining_writers_reap_progress_total 39768
telemt_me_writer_removed_unexpected_total 834
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3287
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36844
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3899
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 241
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35628
telemt_me_writer_teardown_success_total{mode="normal"} 40131
telemt_me_writer_teardown_noop_total 39812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79943
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 166.359865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79943
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 623
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 765
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6541905
telemt_user_connections_current{user="hello"} 3237
telemt_user_octets_from_client{user="hello"} 110995474140 (103.37 GB)
telemt_user_octets_to_client{user="hello"} 2212735403636 (2.01 TB)
telemt_user_unique_ips_current{user="hello"} 1421
telemt_user_unique_ips_recent_window{user="hello"} 433
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 116891.6 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6716583
telemt_connections_bad_total 598968
telemt_connections_current 2880
telemt_connections_me_current 2880
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 223502
telemt_upstream_connect_attempt_total 47501
telemt_upstream_connect_success_total 47102
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 47304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2044
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 899
telemt_me_idle_close_by_peer_total 899
telemt_me_route_drop_no_conn_total 2316556
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5020387
telemt_me_endpoint_quarantine_total 737
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 902
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
telemt_me_writers_active_current 44
telemt_desync_total 23387
telemt_desync_full_logged_total 8007
telemt_desync_suppressed_total 15380
telemt_desync_frames_bucket_total{bucket="1_2"} 5613
telemt_desync_frames_bucket_total{bucket="3_10"} 9081
telemt_desync_frames_bucket_total{bucket="gt_10"} 8693
telemt_pool_swap_total 127
telemt_pool_force_close_total 3765
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 385
telemt_me_draining_writers_reap_progress_total 38186
telemt_me_writer_removed_unexpected_total 879
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3154
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35853
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34421
telemt_me_writer_teardown_success_total{mode="normal"} 39007
telemt_me_writer_teardown_noop_total 38192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77199
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.361912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77199
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 385
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 804
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 4941960
telemt_user_connections_current{user="hello"} 2880
telemt_user_octets_from_client{user="hello"} 145332126261 (135.35 GB)
telemt_user_octets_to_client{user="hello"} 2359067932503 (2.15 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1244
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 116855.5 (32h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6565533
telemt_connections_bad_total 556821
telemt_connections_current 2375
telemt_connections_me_current 2375
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 217516
telemt_upstream_connect_attempt_total 53974
telemt_upstream_connect_success_total 53440
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 53583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 2397
telemt_me_reconnect_success_total 1057
telemt_me_reader_eof_total 991
telemt_me_idle_close_by_peer_total 991
telemt_me_route_drop_no_conn_total 2301669
telemt_me_route_drop_channel_closed_total 137
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4883368
telemt_me_endpoint_quarantine_total 831
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 870
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 23234
telemt_desync_full_logged_total 7879
telemt_desync_suppressed_total 15355
telemt_desync_frames_bucket_total{bucket="1_2"} 5674
telemt_desync_frames_bucket_total{bucket="3_10"} 8906
telemt_desync_frames_bucket_total{bucket="gt_10"} 8654
telemt_pool_swap_total 125
telemt_pool_force_close_total 3634
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 412
telemt_me_draining_writers_reap_progress_total 39289
telemt_me_writer_removed_unexpected_total 982
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3362
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36928
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3399
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 235
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35655
telemt_me_writer_teardown_success_total{mode="normal"} 40290
telemt_me_writer_teardown_noop_total 39301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79591
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 33.768825
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79591
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 412
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 923
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 4878056
telemt_user_connections_current{user="hello"} 2375
telemt_user_octets_from_client{user="hello"} 136544631091 (127.17 GB)
telemt_user_octets_to_client{user="hello"} 2230322561067 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 116895.0 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21024976
telemt_connections_bad_total 1773379
telemt_connections_current 4224
telemt_connections_me_current 4224
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 638816
telemt_upstream_connect_attempt_total 204623
telemt_upstream_connect_success_total 186291
telemt_upstream_connect_fail_total 16475
telemt_upstream_connect_attempts_per_request{bucket="1"} 202766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8952
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16475
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65228
telemt_me_reconnect_success_total 2476
telemt_me_reader_eof_total 1564
telemt_me_idle_close_by_peer_total 1563
telemt_me_route_drop_no_conn_total 39822285
telemt_me_route_drop_channel_closed_total 129
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16900034
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 904
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 915
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32726
telemt_desync_full_logged_total 9874
telemt_desync_suppressed_total 22852
telemt_desync_frames_bucket_total{bucket="1_2"} 7122
telemt_desync_frames_bucket_total{bucket="3_10"} 14515
telemt_desync_frames_bucket_total{bucket="gt_10"} 11089
telemt_pool_swap_total 120
telemt_pool_force_close_total 3887
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 840
telemt_me_draining_writers_reap_progress_total 36866
telemt_me_writer_removed_unexpected_total 2302
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4944
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33970
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3330
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 557
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32979
telemt_me_writer_teardown_success_total{mode="normal"} 38914
telemt_me_writer_teardown_noop_total 36893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75807
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.362888
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75807
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 840
telemt_me_refill_failed_total 3809
telemt_me_writer_restored_same_endpoint_total 1699
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 17034652
telemt_user_connections_current{user="hello"} 4224
telemt_user_octets_from_client{user="hello"} 249020963344 (231.92 GB)
telemt_user_octets_to_client{user="hello"} 1308284376771 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1640
telemt_user_unique_ips_recent_window{user="hello"} 692
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 116862.1 (32h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6342033
telemt_connections_bad_total 608605
telemt_connections_current 2710
telemt_connections_me_current 2709
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 134207
telemt_upstream_connect_attempt_total 62482
telemt_upstream_connect_success_total 61756
telemt_upstream_connect_fail_total 620
telemt_upstream_connect_attempts_per_request{bucket="1"} 62376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 620
telemt_me_reconnect_attempts_total 69881
telemt_me_reconnect_success_total 1876
telemt_me_reader_eof_total 1649
telemt_me_idle_close_by_peer_total 1648
telemt_me_route_drop_no_conn_total 2450897
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4924880
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 890
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
telemt_me_writers_active_current 49
telemt_desync_total 24576
telemt_desync_full_logged_total 8610
telemt_desync_suppressed_total 15966
telemt_desync_frames_bucket_total{bucket="1_2"} 4838
telemt_desync_frames_bucket_total{bucket="3_10"} 9494
telemt_desync_frames_bucket_total{bucket="gt_10"} 10244
telemt_pool_swap_total 121
telemt_pool_force_close_total 3461
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 409
telemt_me_draining_writers_reap_progress_total 41296
telemt_me_writer_removed_unexpected_total 1685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4180
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38833
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3057
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 404
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37835
telemt_me_writer_teardown_success_total{mode="normal"} 43013
telemt_me_writer_teardown_noop_total 41297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84310
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.859665
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84310
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 409
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1566
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4917095
telemt_user_connections_current{user="hello"} 2709
telemt_user_octets_from_client{user="hello"} 128524317508 (119.70 GB)
telemt_user_octets_to_client{user="hello"} 2038578376006 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1194
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 53697.9 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4307953
telemt_connections_bad_total 181520
telemt_connections_current 2417
telemt_connections_me_current 2417
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1701830
telemt_upstream_connect_attempt_total 31329
telemt_upstream_connect_success_total 31120
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 31322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_reconnect_attempts_total 46074
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 1085571
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2130912
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 416
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11581
telemt_desync_full_logged_total 3971
telemt_desync_suppressed_total 7610
telemt_desync_frames_bucket_total{bucket="1_2"} 2220
telemt_desync_frames_bucket_total{bucket="3_10"} 4438
telemt_desync_frames_bucket_total{bucket="gt_10"} 4923
telemt_pool_swap_total 58
telemt_pool_force_close_total 1696
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 20020
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1728
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19108
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18324
telemt_me_writer_teardown_success_total{mode="normal"} 20836
telemt_me_writer_teardown_noop_total 20022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40858
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.563670
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40858
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 2617
telemt_me_writer_restored_same_endpoint_total 915
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2133746
telemt_user_connections_current{user="hello"} 2417
telemt_user_octets_from_client{user="hello"} 57509841852 (53.56 GB)
telemt_user_octets_to_client{user="hello"} 930078999318 (866.20 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1111
telemt_user_unique_ips_recent_window{user="hello"} 365
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 34668.8 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244347
telemt_connections_bad_total 1882
telemt_connections_current 483
telemt_connections_me_current 483
telemt_handshake_timeouts_total 6408
telemt_upstream_connect_attempt_total 16778
telemt_upstream_connect_success_total 16735
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 16774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 407
telemt_me_reconnect_success_total 229
telemt_me_reader_eof_total 230
telemt_me_idle_close_by_peer_total 230
telemt_me_route_drop_no_conn_total 68069
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217255
telemt_me_endpoint_quarantine_total 338
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 302
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1201
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 462
telemt_desync_frames_bucket_total{bucket="gt_10"} 320
telemt_pool_swap_total 38
telemt_pool_force_close_total 846
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 15202
telemt_me_writer_removed_unexpected_total 219
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14466
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 844
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14356
telemt_me_writer_teardown_success_total{mode="normal"} 15432
telemt_me_writer_teardown_noop_total 15202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30634
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.224420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30634
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 198
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 216901
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 3662183516 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 134391237136 (125.16 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 116866.6 (32h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7686657
telemt_connections_bad_total 767048
telemt_connections_current 3175
telemt_connections_me_current 3175
telemt_handshake_timeouts_total 218644
telemt_upstream_connect_attempt_total 46075
telemt_upstream_connect_success_total 45907
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 46038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_reconnect_attempts_total 1684
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 2185739
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5726456
telemt_me_endpoint_quarantine_total 835
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 897
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
telemt_me_writers_active_current 45
telemt_desync_total 22404
telemt_desync_full_logged_total 7384
telemt_desync_suppressed_total 15020
telemt_desync_frames_bucket_total{bucket="1_2"} 5609
telemt_desync_frames_bucket_total{bucket="3_10"} 8136
telemt_desync_frames_bucket_total{bucket="gt_10"} 8659
telemt_pool_swap_total 129
telemt_pool_force_close_total 3438
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 406
telemt_me_draining_writers_reap_progress_total 41590
telemt_me_writer_removed_unexpected_total 858
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3242
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39232
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3350
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38152
telemt_me_writer_teardown_success_total{mode="normal"} 42474
telemt_me_writer_teardown_noop_total 41592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84066
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.812128
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84066
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 406
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 806
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5701134
telemt_user_connections_current{user="hello"} 3175
telemt_user_octets_from_client{user="hello"} 113094338092 (105.33 GB)
telemt_user_octets_to_client{user="hello"} 2660842334200 (2.42 TB)
telemt_user_unique_ips_current{user="hello"} 1209
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 116863.0 (32h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6666671
telemt_connections_bad_total 652858
telemt_connections_current 2734
telemt_connections_me_current 2734
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 181103
telemt_upstream_connect_attempt_total 61922
telemt_upstream_connect_success_total 61456
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 61862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_reconnect_attempts_total 5763
telemt_me_reconnect_success_total 1266
telemt_me_reader_eof_total 1138
telemt_me_idle_close_by_peer_total 1138
telemt_me_seq_mismatch_total 53
telemt_me_route_drop_no_conn_total 2239508
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5093995
telemt_me_endpoint_quarantine_total 916
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 895
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
telemt_desync_total 21112
telemt_desync_full_logged_total 7044
telemt_desync_suppressed_total 14068
telemt_desync_frames_bucket_total{bucket="1_2"} 5351
telemt_desync_frames_bucket_total{bucket="3_10"} 7730
telemt_desync_frames_bucket_total{bucket="gt_10"} 8031
telemt_pool_swap_total 127
telemt_pool_force_close_total 3387
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 40170
telemt_me_writer_removed_unexpected_total 1149
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3796
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37580
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36783
telemt_me_writer_teardown_success_total{mode="normal"} 41376
telemt_me_writer_teardown_noop_total 40174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81550
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.546310
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81550
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 991
telemt_me_writer_restored_fallback_total 71
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5096722
telemt_user_connections_current{user="hello"} 2734
telemt_user_octets_from_client{user="hello"} 95946893737 (89.36 GB)
telemt_user_octets_to_client{user="hello"} 2194668003732 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1171
telemt_user_unique_ips_recent_window{user="hello"} 398
```