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

# Server Metrics 2026-03-22 04:59:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 28358.6 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470158
telemt_connections_bad_total 31840
telemt_connections_current 1074
telemt_connections_me_current 1074
telemt_handshake_timeouts_total 26058
telemt_upstream_connect_attempt_total 11782
telemt_upstream_connect_success_total 11781
telemt_upstream_connect_attempts_per_request{bucket="1"} 11781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 314
telemt_me_reconnect_success_total 184
telemt_me_reader_eof_total 180
telemt_me_idle_close_by_peer_total 180
telemt_me_route_drop_no_conn_total 97735
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387569
telemt_me_endpoint_quarantine_total 223
telemt_me_single_endpoint_shadow_rotate_total 237
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
telemt_desync_total 3482
telemt_desync_full_logged_total 945
telemt_desync_suppressed_total 2537
telemt_desync_frames_bucket_total{bucket="1_2"} 1196
telemt_desync_frames_bucket_total{bucket="3_10"} 1335
telemt_desync_frames_bucket_total{bucket="gt_10"} 951
telemt_pool_swap_total 31
telemt_pool_force_close_total 815
telemt_me_writer_close_signal_drop_total 67
telemt_me_draining_writers_reap_progress_total 10646
telemt_me_writer_removed_unexpected_total 178
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 726
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 810
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9831
telemt_me_writer_teardown_success_total{mode="normal"} 10816
telemt_me_writer_teardown_noop_total 10647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21463
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.496510
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21463
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 67
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 167
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 386615
telemt_user_connections_current{user="hello"} 1074
telemt_user_octets_from_client{user="hello"} 5329670936 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 136665939436 (127.28 GB)
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 41724.9 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 922445
telemt_connections_bad_total 64817
telemt_connections_current 492
telemt_connections_me_current 492
telemt_handshake_timeouts_total 31975
telemt_upstream_connect_attempt_total 22515
telemt_upstream_connect_success_total 22200
telemt_upstream_connect_fail_total 284
telemt_upstream_connect_attempts_per_request{bucket="1"} 22484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 284
telemt_me_reconnect_attempts_total 1668
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 541
telemt_me_idle_close_by_peer_total 541
telemt_me_route_drop_no_conn_total 364889
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 725096
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
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 3110
telemt_desync_full_logged_total 1794
telemt_desync_suppressed_total 1316
telemt_desync_frames_bucket_total{bucket="1_2"} 651
telemt_desync_frames_bucket_total{bucket="3_10"} 1200
telemt_desync_frames_bucket_total{bucket="gt_10"} 1259
telemt_pool_swap_total 45
telemt_pool_force_close_total 1178
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 17359
telemt_me_writer_removed_unexpected_total 516
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16401
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16181
telemt_me_writer_teardown_success_total{mode="normal"} 17887
telemt_me_writer_teardown_noop_total 17359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35246
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.081253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35246
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 464
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 726846
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 11598626559 (10.80 GB)
telemt_user_octets_to_client{user="hello"} 262620703146 (244.58 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 116584.9 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8126729
telemt_connections_bad_total 696782
telemt_connections_current 2519
telemt_connections_me_current 2519
telemt_handshake_timeouts_total 265842
telemt_upstream_connect_attempt_total 43497
telemt_upstream_connect_success_total 43419
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1642
telemt_me_reconnect_success_total 858
telemt_me_reader_eof_total 866
telemt_me_idle_close_by_peer_total 866
telemt_me_route_drop_no_conn_total 4603003
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6535123
telemt_me_endpoint_quarantine_total 746
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 877
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
telemt_me_writers_active_current 46
telemt_desync_total 27456
telemt_desync_full_logged_total 9143
telemt_desync_suppressed_total 18313
telemt_desync_frames_bucket_total{bucket="1_2"} 5924
telemt_desync_frames_bucket_total{bucket="3_10"} 10740
telemt_desync_frames_bucket_total{bucket="gt_10"} 10792
telemt_pool_swap_total 126
telemt_pool_force_close_total 4140
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 623
telemt_me_draining_writers_reap_progress_total 39689
telemt_me_writer_removed_unexpected_total 834
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3286
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36766
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3899
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 241
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35549
telemt_me_writer_teardown_success_total{mode="normal"} 40052
telemt_me_writer_teardown_noop_total 39733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79785
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 166.355275
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79785
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 623
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 765
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6526761
telemt_user_connections_current{user="hello"} 2519
telemt_user_octets_from_client{user="hello"} 110779244468 (103.17 GB)
telemt_user_octets_to_client{user="hello"} 2206201185184 (2.01 TB)
telemt_user_unique_ips_current{user="hello"} 1162
telemt_user_unique_ips_recent_window{user="hello"} 317
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 116586.1 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6700747
telemt_connections_bad_total 598545
telemt_connections_current 2659
telemt_connections_me_current 2659
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 223129
telemt_upstream_connect_attempt_total 47432
telemt_upstream_connect_success_total 47033
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 47235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2044
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 899
telemt_me_idle_close_by_peer_total 899
telemt_me_route_drop_no_conn_total 2311723
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5006995
telemt_me_endpoint_quarantine_total 737
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 901
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
telemt_desync_total 23332
telemt_desync_full_logged_total 7986
telemt_desync_suppressed_total 15346
telemt_desync_frames_bucket_total{bucket="1_2"} 5600
telemt_desync_frames_bucket_total{bucket="3_10"} 9065
telemt_desync_frames_bucket_total{bucket="gt_10"} 8667
telemt_pool_swap_total 127
telemt_pool_force_close_total 3765
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 385
telemt_me_draining_writers_reap_progress_total 38117
telemt_me_writer_removed_unexpected_total 879
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3153
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35785
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34352
telemt_me_writer_teardown_success_total{mode="normal"} 38938
telemt_me_writer_teardown_noop_total 38123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77061
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.359428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77061
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 385
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 804
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 4928587
telemt_user_connections_current{user="hello"} 2659
telemt_user_octets_from_client{user="hello"} 145157427725 (135.19 GB)
telemt_user_octets_to_client{user="hello"} 2352827046731 (2.14 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1187
telemt_user_unique_ips_recent_window{user="hello"} 287
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 116550.9 (32h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6549690
telemt_connections_bad_total 556396
telemt_connections_current 2095
telemt_connections_me_current 2095
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 216792
telemt_upstream_connect_attempt_total 53888
telemt_upstream_connect_success_total 53356
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 53499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 2390
telemt_me_reconnect_success_total 1052
telemt_me_reader_eof_total 986
telemt_me_idle_close_by_peer_total 986
telemt_me_route_drop_no_conn_total 2283978
telemt_me_route_drop_channel_closed_total 135
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4870903
telemt_me_endpoint_quarantine_total 831
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 869
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
telemt_me_writers_active_current 47
telemt_desync_total 23174
telemt_desync_full_logged_total 7856
telemt_desync_suppressed_total 15318
telemt_desync_frames_bucket_total{bucket="1_2"} 5659
telemt_desync_frames_bucket_total{bucket="3_10"} 8881
telemt_desync_frames_bucket_total{bucket="gt_10"} 8634
telemt_pool_swap_total 125
telemt_pool_force_close_total 3634
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 412
telemt_me_draining_writers_reap_progress_total 39234
telemt_me_writer_removed_unexpected_total 977
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3355
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36875
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3399
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 235
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35600
telemt_me_writer_teardown_success_total{mode="normal"} 40230
telemt_me_writer_teardown_noop_total 39246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79476
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 33.767111
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79476
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 412
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 918
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 4865574
telemt_user_connections_current{user="hello"} 2095
telemt_user_octets_from_client{user="hello"} 136380605395 (127.01 GB)
telemt_user_octets_to_client{user="hello"} 2225951632703 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 855
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 116589.5 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20975180
telemt_connections_bad_total 1766857
telemt_connections_current 3445
telemt_connections_me_current 3445
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 637229
telemt_upstream_connect_attempt_total 204522
telemt_upstream_connect_success_total 186197
telemt_upstream_connect_fail_total 16475
telemt_upstream_connect_attempts_per_request{bucket="1"} 202672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8952
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16475
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65224
telemt_me_reconnect_success_total 2473
telemt_me_reader_eof_total 1561
telemt_me_idle_close_by_peer_total 1560
telemt_me_route_drop_no_conn_total 39736943
telemt_me_route_drop_channel_closed_total 129
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16861123
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
telemt_me_writers_active_current 46
telemt_desync_total 32687
telemt_desync_full_logged_total 9860
telemt_desync_suppressed_total 22827
telemt_desync_frames_bucket_total{bucket="1_2"} 7109
telemt_desync_frames_bucket_total{bucket="3_10"} 14497
telemt_desync_frames_bucket_total{bucket="gt_10"} 11081
telemt_pool_swap_total 120
telemt_pool_force_close_total 3887
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 839
telemt_me_draining_writers_reap_progress_total 36797
telemt_me_writer_removed_unexpected_total 2299
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4939
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33903
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3330
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 557
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32910
telemt_me_writer_teardown_success_total{mode="normal"} 38842
telemt_me_writer_teardown_noop_total 36824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75666
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.354548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75666
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 839
telemt_me_refill_failed_total 3809
telemt_me_writer_restored_same_endpoint_total 1696
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 16995745
telemt_user_connections_current{user="hello"} 3445
telemt_user_octets_from_client{user="hello"} 247318381084 (230.33 GB)
telemt_user_octets_to_client{user="hello"} 1305223029655 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1452
telemt_user_unique_ips_recent_window{user="hello"} 460
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 116557.0 (32h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6326629
telemt_connections_bad_total 607721
telemt_connections_current 2547
telemt_connections_me_current 2547
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 133892
telemt_upstream_connect_attempt_total 62382
telemt_upstream_connect_success_total 61656
telemt_upstream_connect_fail_total 620
telemt_upstream_connect_attempts_per_request{bucket="1"} 62276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 620
telemt_me_reconnect_attempts_total 69876
telemt_me_reconnect_success_total 1871
telemt_me_reader_eof_total 1644
telemt_me_idle_close_by_peer_total 1643
telemt_me_route_drop_no_conn_total 2446411
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4911911
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 888
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
telemt_me_writers_active_current 48
telemt_desync_total 24478
telemt_desync_full_logged_total 8585
telemt_desync_suppressed_total 15893
telemt_desync_frames_bucket_total{bucket="1_2"} 4812
telemt_desync_frames_bucket_total{bucket="3_10"} 9464
telemt_desync_frames_bucket_total{bucket="gt_10"} 10202
telemt_pool_swap_total 121
telemt_pool_force_close_total 3461
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 409
telemt_me_draining_writers_reap_progress_total 41221
telemt_me_writer_removed_unexpected_total 1680
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4173
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38760
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3057
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 404
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37760
telemt_me_writer_teardown_success_total{mode="normal"} 42933
telemt_me_writer_teardown_noop_total 41222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84155
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.859051
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84155
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 409
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1561
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4904126
telemt_user_connections_current{user="hello"} 2547
telemt_user_octets_from_client{user="hello"} 128326290420 (119.51 GB)
telemt_user_octets_to_client{user="hello"} 2031821560918 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1120
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 53393.0 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4284661
telemt_connections_bad_total 180998
telemt_connections_current 2045
telemt_connections_me_current 2045
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1694057
telemt_upstream_connect_attempt_total 31250
telemt_upstream_connect_success_total 31041
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 31243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_reconnect_attempts_total 46074
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 1078311
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2117708
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 415
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11453
telemt_desync_full_logged_total 3933
telemt_desync_suppressed_total 7520
telemt_desync_frames_bucket_total{bucket="1_2"} 2174
telemt_desync_frames_bucket_total{bucket="3_10"} 4391
telemt_desync_frames_bucket_total{bucket="gt_10"} 4888
telemt_pool_swap_total 58
telemt_pool_force_close_total 1696
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 19942
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1726
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19032
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18246
telemt_me_writer_teardown_success_total{mode="normal"} 20758
telemt_me_writer_teardown_noop_total 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40702
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.562945
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40702
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 2617
telemt_me_writer_restored_same_endpoint_total 915
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2120672
telemt_user_connections_current{user="hello"} 2045
telemt_user_octets_from_client{user="hello"} 57352230544 (53.41 GB)
telemt_user_octets_to_client{user="hello"} 923385048766 (859.97 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 922
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 34363.9 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241634
telemt_connections_bad_total 1880
telemt_connections_current 481
telemt_connections_me_current 481
telemt_handshake_timeouts_total 6375
telemt_upstream_connect_attempt_total 16660
telemt_upstream_connect_success_total 16617
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 16656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 407
telemt_me_reconnect_success_total 229
telemt_me_reader_eof_total 230
telemt_me_idle_close_by_peer_total 230
telemt_me_route_drop_no_conn_total 67309
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214680
telemt_me_endpoint_quarantine_total 338
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 299
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1195
telemt_desync_full_logged_total 324
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 316
telemt_pool_swap_total 38
telemt_pool_force_close_total 822
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 15056
telemt_me_writer_removed_unexpected_total 219
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 959
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14327
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 820
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14234
telemt_me_writer_teardown_success_total{mode="normal"} 15286
telemt_me_writer_teardown_noop_total 15056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30342
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.219674
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30342
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 198
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 214328
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 3638352376 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 133375474380 (124.22 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 116561.4 (32h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7669400
telemt_connections_bad_total 765961
telemt_connections_current 2643
telemt_connections_me_current 2643
telemt_handshake_timeouts_total 218174
telemt_upstream_connect_attempt_total 45984
telemt_upstream_connect_success_total 45816
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 45947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_reconnect_attempts_total 1684
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 2180723
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5711818
telemt_me_endpoint_quarantine_total 835
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 896
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
telemt_desync_total 22328
telemt_desync_full_logged_total 7353
telemt_desync_suppressed_total 14975
telemt_desync_frames_bucket_total{bucket="1_2"} 5584
telemt_desync_frames_bucket_total{bucket="3_10"} 8114
telemt_desync_frames_bucket_total{bucket="gt_10"} 8630
telemt_pool_swap_total 129
telemt_pool_force_close_total 3438
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 405
telemt_me_draining_writers_reap_progress_total 41499
telemt_me_writer_removed_unexpected_total 858
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3240
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39143
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3350
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38061
telemt_me_writer_teardown_success_total{mode="normal"} 42383
telemt_me_writer_teardown_noop_total 41501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83884
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.810170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83884
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 405
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 806
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5686498
telemt_user_connections_current{user="hello"} 2643
telemt_user_octets_from_client{user="hello"} 112916249752 (105.16 GB)
telemt_user_octets_to_client{user="hello"} 2651895157700 (2.41 TB)
telemt_user_unique_ips_current{user="hello"} 1104
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 116558.2 (32h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6649628
telemt_connections_bad_total 651542
telemt_connections_current 2371
telemt_connections_me_current 2371
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 180848
telemt_upstream_connect_attempt_total 61841
telemt_upstream_connect_success_total 61375
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 61781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_reconnect_attempts_total 5763
telemt_me_reconnect_success_total 1266
telemt_me_reader_eof_total 1138
telemt_me_idle_close_by_peer_total 1138
telemt_me_seq_mismatch_total 53
telemt_me_route_drop_no_conn_total 2235127
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5079487
telemt_me_endpoint_quarantine_total 916
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 894
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
telemt_desync_total 21044
telemt_desync_full_logged_total 7024
telemt_desync_suppressed_total 14020
telemt_desync_frames_bucket_total{bucket="1_2"} 5336
telemt_desync_frames_bucket_total{bucket="3_10"} 7705
telemt_desync_frames_bucket_total{bucket="gt_10"} 8003
telemt_pool_swap_total 127
telemt_pool_force_close_total 3387
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 40089
telemt_me_writer_removed_unexpected_total 1149
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3795
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37500
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36702
telemt_me_writer_teardown_success_total{mode="normal"} 41295
telemt_me_writer_teardown_noop_total 40093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81388
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.544848
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81388
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 991
telemt_me_writer_restored_fallback_total 71
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5082212
telemt_user_connections_current{user="hello"} 2371
telemt_user_octets_from_client{user="hello"} 95752319593 (89.18 GB)
telemt_user_octets_to_client{user="hello"} 2187095268388 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1062
telemt_user_unique_ips_recent_window{user="hello"} 303
```