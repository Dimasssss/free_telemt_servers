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

# Server Metrics 2026-03-22 10:41:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 48893.2 (13h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1314545
telemt_connections_bad_total 68909
telemt_connections_current 2002
telemt_connections_me_current 2002
telemt_handshake_timeouts_total 60593
telemt_upstream_connect_attempt_total 18904
telemt_upstream_connect_success_total 18903
telemt_upstream_connect_attempts_per_request{bucket="1"} 18903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 622
telemt_me_reconnect_success_total 297
telemt_me_reader_eof_total 296
telemt_me_idle_close_by_peer_total 296
telemt_me_route_drop_no_conn_total 716798
telemt_me_route_drop_channel_closed_total 347
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1098949
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 395
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
telemt_desync_total 7242
telemt_desync_full_logged_total 2130
telemt_desync_suppressed_total 5112
telemt_desync_frames_bucket_total{bucket="1_2"} 2103
telemt_desync_frames_bucket_total{bucket="3_10"} 2731
telemt_desync_frames_bucket_total{bucket="gt_10"} 2408
telemt_pool_swap_total 54
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 17213
telemt_me_writer_removed_unexpected_total 291
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16230
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1543
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15635
telemt_me_writer_teardown_success_total{mode="normal"} 17424
telemt_me_writer_teardown_noop_total 17215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34639
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 92.670740
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34639
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1097014
telemt_user_connections_current{user="hello"} 2002
telemt_user_octets_from_client{user="hello"} 17589111056 (16.38 GB)
telemt_user_octets_to_client{user="hello"} 346881495584 (323.06 GB)
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 62259.4 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2114404
telemt_connections_bad_total 175372
telemt_connections_current 1898
telemt_connections_me_current 1898
telemt_handshake_timeouts_total 50733
telemt_upstream_connect_attempt_total 36600
telemt_upstream_connect_success_total 36103
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 36540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3172
telemt_me_reconnect_success_total 1417
telemt_me_reader_eof_total 1304
telemt_me_idle_close_by_peer_total 1304
telemt_me_route_drop_no_conn_total 1600164
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1659197
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 491
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
telemt_me_writers_active_current 40
telemt_desync_total 6856
telemt_desync_full_logged_total 3881
telemt_desync_suppressed_total 2975
telemt_desync_frames_bucket_total{bucket="1_2"} 1562
telemt_desync_frames_bucket_total{bucket="3_10"} 2677
telemt_desync_frames_bucket_total{bucket="gt_10"} 2617
telemt_pool_swap_total 63
telemt_pool_force_close_total 1754
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 25071
telemt_me_writer_removed_unexpected_total 1270
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2727
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23608
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23317
telemt_me_writer_teardown_success_total{mode="normal"} 26335
telemt_me_writer_teardown_noop_total 25071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51406
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.563920
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51406
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1179
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1665170
telemt_user_connections_current{user="hello"} 1898
telemt_user_octets_from_client{user="hello"} 22612659446 (21.06 GB)
telemt_user_octets_to_client{user="hello"} 455796114812 (424.49 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1215
telemt_user_unique_ips_recent_window{user="hello"} 581
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 137119.1 (38h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11441222
telemt_connections_bad_total 969801
telemt_connections_current 4107
telemt_connections_me_current 4107
telemt_handshake_timeouts_total 312259
telemt_upstream_connect_attempt_total 50088
telemt_upstream_connect_success_total 50008
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2142
telemt_me_reconnect_success_total 1101
telemt_me_reader_eof_total 1082
telemt_me_idle_close_by_peer_total 1081
telemt_me_route_drop_no_conn_total 8326169
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9114674
telemt_me_endpoint_quarantine_total 880
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1022
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 37843
telemt_desync_full_logged_total 12252
telemt_desync_suppressed_total 25591
telemt_desync_frames_bucket_total{bucket="1_2"} 8522
telemt_desync_frames_bucket_total{bucket="3_10"} 14709
telemt_desync_frames_bucket_total{bucket="gt_10"} 14612
telemt_pool_swap_total 148
telemt_pool_force_close_total 4973
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 777
telemt_me_draining_writers_reap_progress_total 45679
telemt_me_writer_removed_unexpected_total 1042
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42230
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4639
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40706
telemt_me_writer_teardown_success_total{mode="normal"} 46145
telemt_me_writer_teardown_noop_total 45723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91868
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.480867
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91868
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 777
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 958
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 9103942
telemt_user_connections_current{user="hello"} 4107
telemt_user_octets_from_client{user="hello"} 140879890432 (131.20 GB)
telemt_user_octets_to_client{user="hello"} 2711476975152 (2.47 TB)
telemt_user_unique_ips_current{user="hello"} 1428
telemt_user_unique_ips_recent_window{user="hello"} 750
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 137120.5 (38h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8912231
telemt_connections_bad_total 797594
telemt_connections_current 4129
telemt_connections_me_current 4129
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 273070
telemt_upstream_connect_attempt_total 56520
telemt_upstream_connect_success_total 55951
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 56212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3086
telemt_me_reconnect_success_total 1239
telemt_me_reader_eof_total 1128
telemt_me_idle_close_by_peer_total 1128
telemt_me_route_drop_no_conn_total 3605722
telemt_me_route_drop_channel_closed_total 368
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6636440
telemt_me_endpoint_quarantine_total 869
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1053
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 29979
telemt_desync_full_logged_total 10151
telemt_desync_suppressed_total 19828
telemt_desync_frames_bucket_total{bucket="1_2"} 7307
telemt_desync_frames_bucket_total{bucket="3_10"} 11552
telemt_desync_frames_bucket_total{bucket="gt_10"} 11120
telemt_pool_swap_total 148
telemt_pool_force_close_total 4513
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 44162
telemt_me_writer_removed_unexpected_total 1163
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3851
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41368
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4182
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39649
telemt_me_writer_teardown_success_total{mode="normal"} 45219
telemt_me_writer_teardown_noop_total 44168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89387
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 66.098025
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89387
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1057
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6558075
telemt_user_connections_current{user="hello"} 4129
telemt_user_octets_from_client{user="hello"} 172603262187 (160.75 GB)
telemt_user_octets_to_client{user="hello"} 3026676371126 (2.75 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1635
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 137087.6 (38h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8457143
telemt_connections_bad_total 706571
telemt_connections_current 4080
telemt_connections_me_current 4080
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 272444
telemt_upstream_connect_attempt_total 60840
telemt_upstream_connect_success_total 60138
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3581
telemt_me_reconnect_success_total 1484
telemt_me_reader_eof_total 1371
telemt_me_idle_close_by_peer_total 1371
telemt_me_route_drop_no_conn_total 3570912
telemt_me_route_drop_channel_closed_total 235
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6342128
telemt_me_endpoint_quarantine_total 946
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1004
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 29324
telemt_desync_full_logged_total 9977
telemt_desync_suppressed_total 19347
telemt_desync_frames_bucket_total{bucket="1_2"} 7067
telemt_desync_frames_bucket_total{bucket="3_10"} 11305
telemt_desync_frames_bucket_total{bucket="gt_10"} 10952
telemt_pool_swap_total 145
telemt_pool_force_close_total 4427
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 526
telemt_me_draining_writers_reap_progress_total 44971
telemt_me_writer_removed_unexpected_total 1396
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4229
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42076
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4031
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 396
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40544
telemt_me_writer_teardown_success_total{mode="normal"} 46305
telemt_me_writer_teardown_noop_total 44988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91293
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.628550
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91293
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 526
telemt_me_refill_failed_total 108
telemt_me_writer_restored_same_endpoint_total 1305
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 6333711
telemt_user_connections_current{user="hello"} 4080
telemt_user_octets_from_client{user="hello"} 157082411243 (146.29 GB)
telemt_user_octets_to_client{user="hello"} 2755262605315 (2.51 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1624
telemt_user_unique_ips_recent_window{user="hello"} 600
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 7364.6 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3146898
telemt_connections_bad_total 213790
telemt_connections_current 6837
telemt_connections_me_current 6837
telemt_handshake_timeouts_total 47154
telemt_upstream_connect_attempt_total 9284
telemt_upstream_connect_success_total 8792
telemt_upstream_connect_fail_total 347
telemt_upstream_connect_attempts_per_request{bucket="1"} 9139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2713
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 347
telemt_me_keepalive_timeout_total 373
telemt_me_reconnect_attempts_total 544
telemt_me_reconnect_success_total 217
telemt_me_reader_eof_total 150
telemt_me_idle_close_by_peer_total 150
telemt_me_route_drop_no_conn_total 7203055
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2627477
telemt_me_endpoint_quarantine_total 52
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 58
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
telemt_me_writers_active_current 48
telemt_desync_total 3906
telemt_desync_full_logged_total 1014
telemt_desync_suppressed_total 2892
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 1508
telemt_desync_frames_bucket_total{bucket="gt_10"} 1701
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 1961
telemt_me_writer_removed_unexpected_total 194
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 341
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1799
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 106
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1722
telemt_me_writer_teardown_success_total{mode="normal"} 2140
telemt_me_writer_teardown_noop_total 1962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4102
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.308888
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4102
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 2631607
telemt_user_connections_current{user="hello"} 6837
telemt_user_octets_from_client{user="hello"} 13762548418 (12.82 GB)
telemt_user_octets_to_client{user="hello"} 77614735095 (72.28 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2428
telemt_user_unique_ips_recent_window{user="hello"} 1323
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 137091.3 (38h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8146180
telemt_connections_bad_total 706356
telemt_connections_current 3757
telemt_connections_me_current 3757
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 166371
telemt_upstream_connect_attempt_total 86101
telemt_upstream_connect_success_total 85246
telemt_upstream_connect_fail_total 735
telemt_upstream_connect_attempts_per_request{bucket="1"} 85981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 735
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70647
telemt_me_reconnect_success_total 2174
telemt_me_reader_eof_total 1911
telemt_me_idle_close_by_peer_total 1910
telemt_me_route_drop_no_conn_total 3583198
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6435979
telemt_me_endpoint_quarantine_total 923
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1031
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 32554
telemt_desync_full_logged_total 11231
telemt_desync_suppressed_total 21323
telemt_desync_frames_bucket_total{bucket="1_2"} 6639
telemt_desync_frames_bucket_total{bucket="3_10"} 12522
telemt_desync_frames_bucket_total{bucket="gt_10"} 13393
telemt_pool_swap_total 142
telemt_pool_force_close_total 4130
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 47309
telemt_me_writer_removed_unexpected_total 1940
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44388
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 530
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43179
telemt_me_writer_teardown_success_total{mode="normal"} 49274
telemt_me_writer_teardown_noop_total 47310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96584
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.547381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96584
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 4234
telemt_me_writer_restored_same_endpoint_total 1806
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 6439539
telemt_user_connections_current{user="hello"} 3757
telemt_user_octets_from_client{user="hello"} 155652917219 (144.96 GB)
telemt_user_octets_to_client{user="hello"} 2556575359789 (2.33 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1519
telemt_user_unique_ips_recent_window{user="hello"} 682
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 73927.5 (20h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7170834
telemt_connections_bad_total 268126
telemt_connections_current 5019
telemt_connections_me_current 5019
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2937789
telemt_upstream_connect_attempt_total 38622
telemt_upstream_connect_success_total 38341
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 38615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_reconnect_attempts_total 47683
telemt_me_reconnect_success_total 1327
telemt_me_reader_eof_total 992
telemt_me_idle_close_by_peer_total 992
telemt_me_route_drop_no_conn_total 2202254
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3549213
telemt_me_endpoint_quarantine_total 508
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 560
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_me_writers_active_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 19135
telemt_desync_full_logged_total 6429
telemt_desync_suppressed_total 12706
telemt_desync_frames_bucket_total{bucket="1_2"} 3910
telemt_desync_frames_bucket_total{bucket="3_10"} 7346
telemt_desync_frames_bucket_total{bucket="gt_10"} 7879
telemt_pool_swap_total 78
telemt_pool_force_close_total 2365
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 26372
telemt_me_writer_removed_unexpected_total 1061
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2351
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25106
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 354
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24007
telemt_me_writer_teardown_success_total{mode="normal"} 27457
telemt_me_writer_teardown_noop_total 26378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.990493
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 2695
telemt_me_writer_restored_same_endpoint_total 1184
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3548188
telemt_user_connections_current{user="hello"} 5019
telemt_user_octets_from_client{user="hello"} 84395202416 (78.60 GB)
telemt_user_octets_to_client{user="hello"} 1447626092938 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2006
telemt_user_unique_ips_recent_window{user="hello"} 653
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 54898.1 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559674
telemt_connections_bad_total 3855
telemt_connections_current 940
telemt_connections_me_current 940
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10377
telemt_upstream_connect_attempt_total 28850
telemt_upstream_connect_success_total 28785
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 28843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 299
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1206
telemt_me_reconnect_success_total 513
telemt_me_reader_eof_total 510
telemt_me_idle_close_by_peer_total 510
telemt_me_route_drop_no_conn_total 184158
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506938
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 464
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 92
telemt_desync_total 2605
telemt_desync_full_logged_total 745
telemt_desync_suppressed_total 1860
telemt_desync_frames_bucket_total{bucket="1_2"} 742
telemt_desync_frames_bucket_total{bucket="3_10"} 1015
telemt_desync_frames_bucket_total{bucket="gt_10"} 848
telemt_pool_swap_total 57
telemt_pool_force_close_total 1354
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 23385
telemt_me_writer_removed_unexpected_total 494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1733
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22163
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22031
telemt_me_writer_teardown_success_total{mode="normal"} 23896
telemt_me_writer_teardown_noop_total 23385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47281
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.448857
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47281
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 508905
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 9879350009 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 243086052291 (226.39 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 137095.6 (38h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9903375
telemt_connections_bad_total 1155786
telemt_connections_current 5483
telemt_connections_me_current 5483
telemt_handshake_timeouts_total 265159
telemt_upstream_connect_attempt_total 52634
telemt_upstream_connect_success_total 52434
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 52588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2035
telemt_me_reconnect_success_total 1082
telemt_me_reader_eof_total 1049
telemt_me_idle_close_by_peer_total 1049
telemt_me_route_drop_no_conn_total 2847764
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7378355
telemt_me_endpoint_quarantine_total 964
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1035
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 30002
telemt_desync_full_logged_total 9834
telemt_desync_suppressed_total 20168
telemt_desync_frames_bucket_total{bucket="1_2"} 7365
telemt_desync_frames_bucket_total{bucket="3_10"} 10985
telemt_desync_frames_bucket_total{bucket="gt_10"} 11652
telemt_pool_swap_total 152
telemt_pool_force_close_total 4117
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 47463
telemt_me_writer_removed_unexpected_total 1008
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44669
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43346
telemt_me_writer_teardown_success_total{mode="normal"} 48503
telemt_me_writer_teardown_noop_total 47465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.169107
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7350203
telemt_user_connections_current{user="hello"} 5483
telemt_user_octets_from_client{user="hello"} 142119354364 (132.36 GB)
telemt_user_octets_to_client{user="hello"} 3417035658192 (3.11 TB)
telemt_user_unique_ips_current{user="hello"} 1956
telemt_user_unique_ips_recent_window{user="hello"} 726
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 137092.7 (38h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8615700
telemt_connections_bad_total 973256
telemt_connections_current 4728
telemt_connections_me_current 4728
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 222174
telemt_upstream_connect_attempt_total 77147
telemt_upstream_connect_success_total 76599
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 77078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1968
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_reconnect_attempts_total 6594
telemt_me_reconnect_success_total 1554
telemt_me_reader_eof_total 1378
telemt_me_idle_close_by_peer_total 1378
telemt_me_seq_mismatch_total 65
telemt_me_route_drop_no_conn_total 3094089
telemt_me_route_drop_channel_closed_total 271
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6581352
telemt_me_endpoint_quarantine_total 1066
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1039
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
telemt_me_writers_active_current 44
telemt_desync_total 29108
telemt_desync_full_logged_total 9605
telemt_desync_suppressed_total 19503
telemt_desync_frames_bucket_total{bucket="1_2"} 7174
telemt_desync_frames_bucket_total{bucket="3_10"} 10753
telemt_desync_frames_bucket_total{bucket="gt_10"} 11181
telemt_pool_swap_total 149
telemt_pool_force_close_total 4050
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 498
telemt_me_draining_writers_reap_progress_total 46164
telemt_me_writer_removed_unexpected_total 1396
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4487
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43136
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 299
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42114
telemt_me_writer_teardown_success_total{mode="normal"} 47623
telemt_me_writer_teardown_noop_total 46168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93791
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.647910
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93791
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 498
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1210
telemt_me_writer_restored_fallback_total 89
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6589414
telemt_user_connections_current{user="hello"} 4728
telemt_user_octets_from_client{user="hello"} 119243581713 (111.05 GB)
telemt_user_octets_to_client{user="hello"} 2767548457335 (2.52 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1728
telemt_user_unique_ips_recent_window{user="hello"} 678
```