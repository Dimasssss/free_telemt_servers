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

# Server Metrics 2026-03-22 07:32:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 37568.9 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 791799
telemt_connections_bad_total 49977
telemt_connections_current 1542
telemt_connections_me_current 1542
telemt_handshake_timeouts_total 37632
telemt_upstream_connect_attempt_total 15211
telemt_upstream_connect_success_total 15210
telemt_upstream_connect_attempts_per_request{bucket="1"} 15210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 427
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 307823
telemt_me_route_drop_channel_closed_total 114
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 656190
telemt_me_endpoint_quarantine_total 269
telemt_me_single_endpoint_shadow_rotate_total 306
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
telemt_desync_total 5241
telemt_desync_full_logged_total 1482
telemt_desync_suppressed_total 3759
telemt_desync_frames_bucket_total{bucket="1_2"} 1669
telemt_desync_frames_bucket_total{bucket="3_10"} 1965
telemt_desync_frames_bucket_total{bucket="gt_10"} 1607
telemt_pool_swap_total 41
telemt_pool_force_close_total 1120
telemt_me_writer_close_signal_drop_total 116
telemt_me_draining_writers_reap_progress_total 13786
telemt_me_writer_removed_unexpected_total 233
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 956
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13038
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12666
telemt_me_writer_teardown_success_total{mode="normal"} 13994
telemt_me_writer_teardown_noop_total 13787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27781
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.830412
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27781
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 116
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 219
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 654985
telemt_user_connections_current{user="hello"} 1542
telemt_user_octets_from_client{user="hello"} 8956939444 (8.34 GB)
telemt_user_octets_to_client{user="hello"} 222981055688 (207.67 GB)
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 50935.2 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1270646
telemt_connections_bad_total 122907
telemt_connections_current 1266
telemt_connections_me_current 1266
telemt_handshake_timeouts_total 39451
telemt_upstream_connect_attempt_total 26728
telemt_upstream_connect_success_total 26330
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 26676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1985
telemt_me_reconnect_success_total 813
telemt_me_reader_eof_total 703
telemt_me_idle_close_by_peer_total 703
telemt_me_route_drop_no_conn_total 486316
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 958922
telemt_me_endpoint_quarantine_total 469
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 407
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 4150
telemt_desync_full_logged_total 2423
telemt_desync_suppressed_total 1727
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1608
telemt_desync_frames_bucket_total{bucket="gt_10"} 1661
telemt_pool_swap_total 54
telemt_pool_force_close_total 1450
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 20850
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1868
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19644
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1379
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19400
telemt_me_writer_teardown_success_total{mode="normal"} 21512
telemt_me_writer_teardown_noop_total 20850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.384112
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 619
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 960610
telemt_user_connections_current{user="hello"} 1266
telemt_user_octets_from_client{user="hello"} 15168597250 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 349602519423 (325.59 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 451
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 125795.1 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9106524
telemt_connections_bad_total 835332
telemt_connections_current 4626
telemt_connections_me_current 4626
telemt_handshake_timeouts_total 283330
telemt_upstream_connect_attempt_total 46448
telemt_upstream_connect_success_total 46369
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1797
telemt_me_reconnect_success_total 923
telemt_me_reader_eof_total 925
telemt_me_idle_close_by_peer_total 925
telemt_me_route_drop_no_conn_total 4926215
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7166260
telemt_me_endpoint_quarantine_total 791
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 945
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
telemt_me_writers_active_current 50
telemt_desync_total 31166
telemt_desync_full_logged_total 10301
telemt_desync_suppressed_total 20865
telemt_desync_frames_bucket_total{bucket="1_2"} 6772
telemt_desync_frames_bucket_total{bucket="3_10"} 12103
telemt_desync_frames_bucket_total{bucket="gt_10"} 12291
telemt_pool_swap_total 136
telemt_pool_force_close_total 4487
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 42399
telemt_me_writer_removed_unexpected_total 889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3520
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39258
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4217
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 270
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37912
telemt_me_writer_teardown_success_total{mode="normal"} 42778
telemt_me_writer_teardown_noop_total 42443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85221
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.969555
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85221
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 7156872
telemt_user_connections_current{user="hello"} 4626
telemt_user_octets_from_client{user="hello"} 120351646216 (112.09 GB)
telemt_user_octets_to_client{user="hello"} 2443801456280 (2.22 TB)
telemt_user_unique_ips_current{user="hello"} 1834
telemt_user_unique_ips_recent_window{user="hello"} 719
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 125796.3 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7498006
telemt_connections_bad_total 661937
telemt_connections_current 4003
telemt_connections_me_current 4003
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 245128
telemt_upstream_connect_attempt_total 50427
telemt_upstream_connect_success_total 50021
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 50230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 562
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2632
telemt_me_reconnect_success_total 991
telemt_me_reader_eof_total 958
telemt_me_idle_close_by_peer_total 958
telemt_me_route_drop_no_conn_total 2514653
telemt_me_route_drop_channel_closed_total 306
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5555884
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 967
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
telemt_me_writers_active_current 44
telemt_desync_total 25551
telemt_desync_full_logged_total 8767
telemt_desync_suppressed_total 16784
telemt_desync_frames_bucket_total{bucket="1_2"} 6095
telemt_desync_frames_bucket_total{bucket="3_10"} 9925
telemt_desync_frames_bucket_total{bucket="gt_10"} 9531
telemt_pool_swap_total 137
telemt_pool_force_close_total 4105
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 40845
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3389
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38309
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36740
telemt_me_writer_teardown_success_total{mode="normal"} 41698
telemt_me_writer_teardown_noop_total 40851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.454746
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82549
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 867
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 5476803
telemt_user_connections_current{user="hello"} 4003
telemt_user_octets_from_client{user="hello"} 154966909489 (144.32 GB)
telemt_user_octets_to_client{user="hello"} 2650160375383 (2.41 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1575
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 125761.6 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7242869
telemt_connections_bad_total 596740
telemt_connections_current 3480
telemt_connections_me_current 3480
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241043
telemt_upstream_connect_attempt_total 57066
telemt_upstream_connect_success_total 56400
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 56547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2736
telemt_me_reconnect_success_total 1189
telemt_me_reader_eof_total 1097
telemt_me_idle_close_by_peer_total 1097
telemt_me_route_drop_no_conn_total 2922441
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5409875
telemt_me_endpoint_quarantine_total 884
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 930
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 25213
telemt_desync_full_logged_total 8602
telemt_desync_suppressed_total 16611
telemt_desync_frames_bucket_total{bucket="1_2"} 6117
telemt_desync_frames_bucket_total{bucket="3_10"} 9676
telemt_desync_frames_bucket_total{bucket="gt_10"} 9420
telemt_pool_swap_total 134
telemt_pool_force_close_total 3955
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 456
telemt_me_draining_writers_reap_progress_total 41794
telemt_me_writer_removed_unexpected_total 1107
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3705
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39200
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 293
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37839
telemt_me_writer_teardown_success_total{mode="normal"} 42905
telemt_me_writer_teardown_noop_total 41806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84711
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.682744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84711
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 456
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5403349
telemt_user_connections_current{user="hello"} 3480
telemt_user_octets_from_client{user="hello"} 143312593235 (133.47 GB)
telemt_user_octets_to_client{user="hello"} 2408502777859 (2.19 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1471
telemt_user_unique_ips_recent_window{user="hello"} 513
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 125799.5 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23202746
telemt_connections_bad_total 1932768
telemt_connections_current 5591
telemt_connections_me_current 5591
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 682063
telemt_upstream_connect_attempt_total 240682
telemt_upstream_connect_success_total 220946
telemt_upstream_connect_fail_total 17756
telemt_upstream_connect_attempts_per_request{bucket="1"} 238702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17756
telemt_me_keepalive_timeout_total 400
telemt_me_reconnect_attempts_total 66507
telemt_me_reconnect_success_total 2687
telemt_me_reader_eof_total 1667
telemt_me_idle_close_by_peer_total 1665
telemt_me_route_drop_no_conn_total 44325270
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18704230
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 982
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 990
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_desync_total 36123
telemt_desync_full_logged_total 10782
telemt_desync_suppressed_total 25341
telemt_desync_frames_bucket_total{bucket="1_2"} 8003
telemt_desync_frames_bucket_total{bucket="3_10"} 16003
telemt_desync_frames_bucket_total{bucket="gt_10"} 12117
telemt_pool_swap_total 130
telemt_pool_force_close_total 4122
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 955
telemt_me_draining_writers_reap_progress_total 39262
telemt_me_writer_removed_unexpected_total 2490
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5341
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36142
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3534
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 588
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35140
telemt_me_writer_teardown_success_total{mode="normal"} 41483
telemt_me_writer_teardown_noop_total 39294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80777
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 281.672260
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80777
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 955
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1816
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 18870063
telemt_user_connections_current{user="hello"} 5591
telemt_user_octets_from_client{user="hello"} 273432864967 (254.65 GB)
telemt_user_octets_to_client{user="hello"} 1410931924419 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2074
telemt_user_unique_ips_recent_window{user="hello"} 1142
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 125767.1 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6911458
telemt_connections_bad_total 634358
telemt_connections_current 4189
telemt_connections_me_current 4189
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 143079
telemt_upstream_connect_attempt_total 65455
telemt_upstream_connect_success_total 64710
telemt_upstream_connect_fail_total 639
telemt_upstream_connect_attempts_per_request{bucket="1"} 65349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 639
telemt_me_reconnect_attempts_total 70048
telemt_me_reconnect_success_total 1927
telemt_me_reader_eof_total 1704
telemt_me_idle_close_by_peer_total 1703
telemt_me_route_drop_no_conn_total 2655382
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5411330
telemt_me_endpoint_quarantine_total 838
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 955
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
telemt_me_writers_active_current 44
telemt_desync_total 27216
telemt_desync_full_logged_total 9478
telemt_desync_suppressed_total 17738
telemt_desync_frames_bucket_total{bucket="1_2"} 5442
telemt_desync_frames_bucket_total{bucket="3_10"} 10453
telemt_desync_frames_bucket_total{bucket="gt_10"} 11321
telemt_pool_swap_total 131
telemt_pool_force_close_total 3766
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 444
telemt_me_draining_writers_reap_progress_total 43990
telemt_me_writer_removed_unexpected_total 1735
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4403
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41359
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3348
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40224
telemt_me_writer_teardown_success_total{mode="normal"} 45762
telemt_me_writer_teardown_noop_total 43991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89753
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.041422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89753
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 444
telemt_me_refill_failed_total 4219
telemt_me_writer_restored_same_endpoint_total 1609
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 5402449
telemt_user_connections_current{user="hello"} 4189
telemt_user_octets_from_client{user="hello"} 137645332228 (128.19 GB)
telemt_user_octets_to_client{user="hello"} 2259875166026 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1647
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 62603.1 (17h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5195371
telemt_connections_bad_total 209903
telemt_connections_current 3730
telemt_connections_me_current 3730
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2064044
telemt_upstream_connect_attempt_total 34387
telemt_upstream_connect_success_total 34148
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 34380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_reconnect_attempts_total 46241
telemt_me_reconnect_success_total 1082
telemt_me_reader_eof_total 772
telemt_me_idle_close_by_peer_total 772
telemt_me_route_drop_no_conn_total 1270669
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2586941
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 483
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 13803
telemt_desync_full_logged_total 4750
telemt_desync_suppressed_total 9053
telemt_desync_frames_bucket_total{bucket="1_2"} 2733
telemt_desync_frames_bucket_total{bucket="3_10"} 5277
telemt_desync_frames_bucket_total{bucket="gt_10"} 5793
telemt_pool_swap_total 68
telemt_pool_force_close_total 2002
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 182
telemt_me_draining_writers_reap_progress_total 22744
telemt_me_writer_removed_unexpected_total 842
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1916
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21692
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1772
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20742
telemt_me_writer_teardown_success_total{mode="normal"} 23608
telemt_me_writer_teardown_noop_total 22746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46354
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.159769
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46354
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 182
telemt_me_refill_failed_total 2623
telemt_me_writer_restored_same_endpoint_total 963
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2588554
telemt_user_connections_current{user="hello"} 3730
telemt_user_octets_from_client{user="hello"} 65679202104 (61.17 GB)
telemt_user_octets_to_client{user="hello"} 1149411623854 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1533
telemt_user_unique_ips_recent_window{user="hello"} 565
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 43573.8 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343528
telemt_connections_bad_total 2431
telemt_connections_current 878
telemt_connections_me_current 878
telemt_handshake_timeouts_total 7591
telemt_upstream_connect_attempt_total 20839
telemt_upstream_connect_success_total 20785
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 20835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 902
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 302
telemt_me_idle_close_by_peer_total 302
telemt_me_route_drop_no_conn_total 105883
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311745
telemt_me_endpoint_quarantine_total 417
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 379
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
telemt_me_writers_active_current 44
telemt_desync_total 1474
telemt_desync_full_logged_total 417
telemt_desync_suppressed_total 1057
telemt_desync_frames_bucket_total{bucket="1_2"} 475
telemt_desync_frames_bucket_total{bucket="3_10"} 567
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 48
telemt_pool_force_close_total 1086
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 18850
telemt_me_writer_removed_unexpected_total 289
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1235
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17917
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1084
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17764
telemt_me_writer_teardown_success_total{mode="normal"} 19152
telemt_me_writer_teardown_noop_total 18850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38002
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.587205
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38002
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 260
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 311199
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 5222387524 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 173601104868 (161.68 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 125771.5 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8457994
telemt_connections_bad_total 916109
telemt_connections_current 4457
telemt_connections_me_current 4457
telemt_handshake_timeouts_total 238207
telemt_upstream_connect_attempt_total 49245
telemt_upstream_connect_success_total 49064
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 49206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 1832
telemt_me_reconnect_success_total 995
telemt_me_reader_eof_total 972
telemt_me_idle_close_by_peer_total 972
telemt_me_route_drop_no_conn_total 2371124
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6281285
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 959
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
telemt_me_writers_active_current 44
telemt_desync_total 25024
telemt_desync_full_logged_total 8227
telemt_desync_suppressed_total 16797
telemt_desync_frames_bucket_total{bucket="1_2"} 6217
telemt_desync_frames_bucket_total{bucket="3_10"} 9108
telemt_desync_frames_bucket_total{bucket="gt_10"} 9699
telemt_pool_swap_total 139
telemt_pool_force_close_total 3716
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 443
telemt_me_draining_writers_reap_progress_total 44444
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3512
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41894
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3623
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40728
telemt_me_writer_teardown_success_total{mode="normal"} 45406
telemt_me_writer_teardown_noop_total 44446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89852
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.494387
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89852
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 443
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 879
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6255048
telemt_user_connections_current{user="hello"} 4457
telemt_user_octets_from_client{user="hello"} 123605426004 (115.12 GB)
telemt_user_octets_to_client{user="hello"} 2935433601524 (2.67 TB)
telemt_user_unique_ips_current{user="hello"} 1744
telemt_user_unique_ips_recent_window{user="hello"} 662
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 125768.0 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7383207
telemt_connections_bad_total 790915
telemt_connections_current 4290
telemt_connections_me_current 4290
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 197574
telemt_upstream_connect_attempt_total 65234
telemt_upstream_connect_success_total 64737
telemt_upstream_connect_fail_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 65171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 434
telemt_me_reconnect_attempts_total 6022
telemt_me_reconnect_success_total 1389
telemt_me_reader_eof_total 1252
telemt_me_idle_close_by_peer_total 1252
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2471456
telemt_me_route_drop_channel_closed_total 202
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5620918
telemt_me_endpoint_quarantine_total 987
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 959
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 24033
telemt_desync_full_logged_total 7995
telemt_desync_suppressed_total 16038
telemt_desync_frames_bucket_total{bucket="1_2"} 5938
telemt_desync_frames_bucket_total{bucket="3_10"} 8820
telemt_desync_frames_bucket_total{bucket="gt_10"} 9275
telemt_pool_swap_total 136
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 443
telemt_me_draining_writers_reap_progress_total 43083
telemt_me_writer_removed_unexpected_total 1267
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4097
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40314
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39421
telemt_me_writer_teardown_success_total{mode="normal"} 44411
telemt_me_writer_teardown_noop_total 43087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87498
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.568324
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87498
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 443
telemt_me_refill_failed_total 267
telemt_me_writer_restored_same_endpoint_total 1087
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 5622522
telemt_user_connections_current{user="hello"} 4290
telemt_user_octets_from_client{user="hello"} 104013479425 (96.87 GB)
telemt_user_octets_to_client{user="hello"} 2443612611752 (2.22 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1626
telemt_user_unique_ips_recent_window{user="hello"} 592
```