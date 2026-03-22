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

# Server Metrics 2026-03-22 07:57:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 39094.7 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850161
telemt_connections_bad_total 52431
telemt_connections_current 1487
telemt_connections_me_current 1487
telemt_handshake_timeouts_total 40735
telemt_upstream_connect_attempt_total 15705
telemt_upstream_connect_success_total 15704
telemt_upstream_connect_attempts_per_request{bucket="1"} 15704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 432
telemt_me_reconnect_success_total 243
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 325689
telemt_me_route_drop_channel_closed_total 125
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 703664
telemt_me_endpoint_quarantine_total 279
telemt_me_single_endpoint_shadow_rotate_total 319
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
telemt_me_writers_active_current 45
telemt_desync_total 5590
telemt_desync_full_logged_total 1572
telemt_desync_suppressed_total 4018
telemt_desync_frames_bucket_total{bucket="1_2"} 1741
telemt_desync_frames_bucket_total{bucket="3_10"} 2088
telemt_desync_frames_bucket_total{bucket="gt_10"} 1761
telemt_pool_swap_total 43
telemt_pool_force_close_total 1205
telemt_me_writer_close_signal_drop_total 125
telemt_me_draining_writers_reap_progress_total 14268
telemt_me_writer_removed_unexpected_total 238
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 988
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13471
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13063
telemt_me_writer_teardown_success_total{mode="normal"} 14459
telemt_me_writer_teardown_noop_total 14269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28728
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 39.399791
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28728
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 125
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 702401
telemt_user_connections_current{user="hello"} 1487
telemt_user_octets_from_client{user="hello"} 10042393792 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 239590518032 (223.14 GB)
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 52460.8 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1339392
telemt_connections_bad_total 128415
telemt_connections_current 1840
telemt_connections_me_current 1840
telemt_handshake_timeouts_total 40735
telemt_upstream_connect_attempt_total 27368
telemt_upstream_connect_success_total 26956
telemt_upstream_connect_fail_total 360
telemt_upstream_connect_attempts_per_request{bucket="1"} 27316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 360
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2036
telemt_me_reconnect_success_total 865
telemt_me_reader_eof_total 754
telemt_me_idle_close_by_peer_total 754
telemt_me_route_drop_no_conn_total 536930
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1010122
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 420
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 87
telemt_desync_total 4384
telemt_desync_full_logged_total 2565
telemt_desync_suppressed_total 1819
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 1689
telemt_desync_frames_bucket_total{bucket="gt_10"} 1752
telemt_pool_swap_total 55
telemt_pool_force_close_total 1480
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 21362
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20130
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19882
telemt_me_writer_teardown_success_total{mode="normal"} 22075
telemt_me_writer_teardown_noop_total 21362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43437
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.909927
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43437
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 667
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 1011784
telemt_user_connections_current{user="hello"} 1840
telemt_user_octets_from_client{user="hello"} 15854023498 (14.77 GB)
telemt_user_octets_to_client{user="hello"} 361140434919 (336.34 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 127321.6 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9321441
telemt_connections_bad_total 847648
telemt_connections_current 3701
telemt_connections_me_current 3701
telemt_handshake_timeouts_total 285897
telemt_upstream_connect_attempt_total 46926
telemt_upstream_connect_success_total 46846
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1838
telemt_me_reconnect_success_total 932
telemt_me_reader_eof_total 936
telemt_me_idle_close_by_peer_total 936
telemt_me_route_drop_no_conn_total 5077602
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7324289
telemt_me_endpoint_quarantine_total 802
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 955
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
telemt_me_writers_active_current 44
telemt_desync_total 31810
telemt_desync_full_logged_total 10493
telemt_desync_suppressed_total 21317
telemt_desync_frames_bucket_total{bucket="1_2"} 6946
telemt_desync_frames_bucket_total{bucket="3_10"} 12343
telemt_desync_frames_bucket_total{bucket="gt_10"} 12521
telemt_pool_swap_total 138
telemt_pool_force_close_total 4564
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 42849
telemt_me_writer_removed_unexpected_total 900
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3566
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39661
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4287
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38285
telemt_me_writer_teardown_success_total{mode="normal"} 43227
telemt_me_writer_teardown_noop_total 42893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86120
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 182.163107
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86120
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 830
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 7314708
telemt_user_connections_current{user="hello"} 3701
telemt_user_octets_from_client{user="hello"} 122391578936 (113.99 GB)
telemt_user_octets_to_client{user="hello"} 2479477009320 (2.26 TB)
telemt_user_unique_ips_current{user="hello"} 1516
telemt_user_unique_ips_recent_window{user="hello"} 617
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 127322.1 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7663574
telemt_connections_bad_total 681459
telemt_connections_current 3686
telemt_connections_me_current 3686
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 249418
telemt_upstream_connect_attempt_total 53147
telemt_upstream_connect_success_total 52680
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 52920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2799
telemt_me_reconnect_success_total 1047
telemt_me_reader_eof_total 966
telemt_me_idle_close_by_peer_total 966
telemt_me_route_drop_no_conn_total 2564162
telemt_me_route_drop_channel_closed_total 312
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5674408
telemt_me_endpoint_quarantine_total 808
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 983
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
telemt_me_writers_active_current 43
telemt_desync_total 26002
telemt_desync_full_logged_total 8906
telemt_desync_suppressed_total 17096
telemt_desync_frames_bucket_total{bucket="1_2"} 6219
telemt_desync_frames_bucket_total{bucket="3_10"} 10072
telemt_desync_frames_bucket_total{bucket="gt_10"} 9711
telemt_pool_swap_total 139
telemt_pool_force_close_total 4140
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 41268
telemt_me_writer_removed_unexpected_total 991
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3501
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38677
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37128
telemt_me_writer_teardown_success_total{mode="normal"} 42178
telemt_me_writer_teardown_noop_total 41274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83452
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.662358
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83452
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 888
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5597282
telemt_user_connections_current{user="hello"} 3686
telemt_user_octets_from_client{user="hello"} 157128573619 (146.34 GB)
telemt_user_octets_to_client{user="hello"} 2694563990890 (2.45 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1515
telemt_user_unique_ips_recent_window{user="hello"} 544
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 127286.1 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7405953
telemt_connections_bad_total 611244
telemt_connections_current 3540
telemt_connections_me_current 3540
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 245400
telemt_upstream_connect_attempt_total 57559
telemt_upstream_connect_success_total 56889
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2739
telemt_me_reconnect_success_total 1191
telemt_me_reader_eof_total 1099
telemt_me_idle_close_by_peer_total 1099
telemt_me_route_drop_no_conn_total 2982404
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5519379
telemt_me_endpoint_quarantine_total 897
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 942
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 25787
telemt_desync_full_logged_total 8806
telemt_desync_suppressed_total 16981
telemt_desync_frames_bucket_total{bucket="1_2"} 6237
telemt_desync_frames_bucket_total{bucket="3_10"} 9910
telemt_desync_frames_bucket_total{bucket="gt_10"} 9640
telemt_pool_swap_total 136
telemt_pool_force_close_total 4045
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 459
telemt_me_draining_writers_reap_progress_total 42284
telemt_me_writer_removed_unexpected_total 1109
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3740
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39636
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3743
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38239
telemt_me_writer_teardown_success_total{mode="normal"} 43376
telemt_me_writer_teardown_noop_total 42296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85672
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.366082
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85672
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 459
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1032
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5512588
telemt_user_connections_current{user="hello"} 3540
telemt_user_octets_from_client{user="hello"} 145103410119 (135.14 GB)
telemt_user_octets_to_client{user="hello"} 2453973204651 (2.23 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1476
telemt_user_unique_ips_recent_window{user="hello"} 527
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 127325.7 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23720880
telemt_connections_bad_total 1960621
telemt_connections_current 5850
telemt_connections_me_current 5850
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 690261
telemt_upstream_connect_attempt_total 241174
telemt_upstream_connect_success_total 221424
telemt_upstream_connect_fail_total 17758
telemt_upstream_connect_attempts_per_request{bucket="1"} 239182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17758
telemt_me_keepalive_timeout_total 414
telemt_me_reconnect_attempts_total 66515
telemt_me_reconnect_success_total 2694
telemt_me_reader_eof_total 1674
telemt_me_idle_close_by_peer_total 1672
telemt_me_route_drop_no_conn_total 45715592
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19152362
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 991
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 1002
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
telemt_me_writers_active_current 46
telemt_desync_total 37091
telemt_desync_full_logged_total 11000
telemt_desync_suppressed_total 26091
telemt_desync_frames_bucket_total{bucket="1_2"} 8227
telemt_desync_frames_bucket_total{bucket="3_10"} 16390
telemt_desync_frames_bucket_total{bucket="gt_10"} 12474
telemt_pool_swap_total 132
telemt_pool_force_close_total 4184
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 965
telemt_me_draining_writers_reap_progress_total 39702
telemt_me_writer_removed_unexpected_total 2497
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36552
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 589
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35518
telemt_me_writer_teardown_success_total{mode="normal"} 41930
telemt_me_writer_teardown_noop_total 39734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81664
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.007781
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81664
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 965
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1822
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 19317985
telemt_user_connections_current{user="hello"} 5850
telemt_user_octets_from_client{user="hello"} 276367874619 (257.39 GB)
telemt_user_octets_to_client{user="hello"} 1426583495615 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2095
telemt_user_unique_ips_recent_window{user="hello"} 1142
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 127293.0 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7034881
telemt_connections_bad_total 641206
telemt_connections_current 3236
telemt_connections_me_current 3236
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 145258
telemt_upstream_connect_attempt_total 65995
telemt_upstream_connect_success_total 65227
telemt_upstream_connect_fail_total 662
telemt_upstream_connect_attempts_per_request{bucket="1"} 65889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 662
telemt_me_reconnect_attempts_total 70198
telemt_me_reconnect_success_total 1960
telemt_me_reader_eof_total 1727
telemt_me_idle_close_by_peer_total 1726
telemt_me_route_drop_no_conn_total 2700612
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5515954
telemt_me_endpoint_quarantine_total 853
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 968
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
telemt_me_writers_active_current 45
telemt_desync_total 27774
telemt_desync_full_logged_total 9679
telemt_desync_suppressed_total 18095
telemt_desync_frames_bucket_total{bucket="1_2"} 5553
telemt_desync_frames_bucket_total{bucket="3_10"} 10671
telemt_desync_frames_bucket_total{bucket="gt_10"} 11550
telemt_pool_swap_total 133
telemt_pool_force_close_total 3832
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 449
telemt_me_draining_writers_reap_progress_total 44443
telemt_me_writer_removed_unexpected_total 1758
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4459
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 426
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40611
telemt_me_writer_teardown_success_total{mode="normal"} 46226
telemt_me_writer_teardown_noop_total 44444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90670
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.157110
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90670
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 449
telemt_me_refill_failed_total 4224
telemt_me_writer_restored_same_endpoint_total 1632
telemt_me_writer_restored_fallback_total 39
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5506815
telemt_user_connections_current{user="hello"} 3236
telemt_user_octets_from_client{user="hello"} 139423888920 (129.85 GB)
telemt_user_octets_to_client{user="hello"} 2301251505326 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1359
telemt_user_unique_ips_recent_window{user="hello"} 550
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 64129.1 (17h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5381958
telemt_connections_bad_total 214983
telemt_connections_current 4315
telemt_connections_me_current 4315
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2142514
telemt_upstream_connect_attempt_total 34892
telemt_upstream_connect_success_total 34646
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 34885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_reconnect_attempts_total 46360
telemt_me_reconnect_success_total 1132
telemt_me_reader_eof_total 824
telemt_me_idle_close_by_peer_total 824
telemt_me_route_drop_no_conn_total 1312346
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2682984
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 492
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
telemt_me_writers_active_current 85
telemt_me_writers_warm_current 1
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 14403
telemt_desync_full_logged_total 4950
telemt_desync_suppressed_total 9453
telemt_desync_frames_bucket_total{bucket="1_2"} 2817
telemt_desync_frames_bucket_total{bucket="3_10"} 5540
telemt_desync_frames_bucket_total{bucket="gt_10"} 6046
telemt_pool_swap_total 69
telemt_pool_force_close_total 2031
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 23111
telemt_me_writer_removed_unexpected_total 894
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22040
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21080
telemt_me_writer_teardown_success_total{mode="normal"} 24027
telemt_me_writer_teardown_noop_total 23113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47140
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.282598
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47140
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 2627
telemt_me_writer_restored_same_endpoint_total 1011
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2684514
telemt_user_connections_current{user="hello"} 4315
telemt_user_octets_from_client{user="hello"} 67897683868 (63.23 GB)
telemt_user_octets_to_client{user="hello"} 1190639722442 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1812
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 45099.5 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368314
telemt_connections_bad_total 2507
telemt_connections_current 815
telemt_connections_me_current 815
telemt_handshake_timeouts_total 7920
telemt_upstream_connect_attempt_total 21412
telemt_upstream_connect_success_total 21358
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 21408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 927
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 312
telemt_me_idle_close_by_peer_total 312
telemt_me_route_drop_no_conn_total 114358
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334362
telemt_me_endpoint_quarantine_total 432
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 387
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
telemt_me_writers_active_current 43
telemt_desync_total 1547
telemt_desync_full_logged_total 441
telemt_desync_suppressed_total 1106
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 596
telemt_desync_frames_bucket_total{bucket="gt_10"} 467
telemt_pool_swap_total 50
telemt_pool_force_close_total 1112
telemt_me_writer_close_signal_drop_total 41
telemt_me_draining_writers_reap_progress_total 19316
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1273
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18355
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1110
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18204
telemt_me_writer_teardown_success_total{mode="normal"} 19628
telemt_me_writer_teardown_noop_total 19316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38944
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.802254
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38944
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 41
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 267
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 333803
telemt_user_connections_current{user="hello"} 815
telemt_user_octets_from_client{user="hello"} 5916490908 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 180137639284 (167.77 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 127297.7 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8627902
telemt_connections_bad_total 950788
telemt_connections_current 4447
telemt_connections_me_current 4447
telemt_handshake_timeouts_total 242412
telemt_upstream_connect_attempt_total 49740
telemt_upstream_connect_success_total 49559
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 49701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 1837
telemt_me_reconnect_success_total 999
telemt_me_reader_eof_total 977
telemt_me_idle_close_by_peer_total 977
telemt_me_route_drop_no_conn_total 2413364
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6406289
telemt_me_endpoint_quarantine_total 900
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 970
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
telemt_desync_total 25632
telemt_desync_full_logged_total 8431
telemt_desync_suppressed_total 17201
telemt_desync_frames_bucket_total{bucket="1_2"} 6343
telemt_desync_frames_bucket_total{bucket="3_10"} 9329
telemt_desync_frames_bucket_total{bucket="gt_10"} 9960
telemt_pool_swap_total 141
telemt_pool_force_close_total 3779
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 451
telemt_me_draining_writers_reap_progress_total 44896
telemt_me_writer_removed_unexpected_total 938
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3557
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42306
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3683
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 96
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41117
telemt_me_writer_teardown_success_total{mode="normal"} 45863
telemt_me_writer_teardown_noop_total 44898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90761
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.557179
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90761
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 451
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 883
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6379682
telemt_user_connections_current{user="hello"} 4447
telemt_user_octets_from_client{user="hello"} 125490561792 (116.87 GB)
telemt_user_octets_to_client{user="hello"} 2993472384344 (2.72 TB)
telemt_user_unique_ips_current{user="hello"} 1666
telemt_user_unique_ips_recent_window{user="hello"} 605
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 127294.8 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7537845
telemt_connections_bad_total 825111
telemt_connections_current 4128
telemt_connections_me_current 4128
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 201615
telemt_upstream_connect_attempt_total 65799
telemt_upstream_connect_success_total 65293
telemt_upstream_connect_fail_total 443
telemt_upstream_connect_attempts_per_request{bucket="1"} 65736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 625
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 443
telemt_me_reconnect_attempts_total 6159
telemt_me_reconnect_success_total 1413
telemt_me_reader_eof_total 1274
telemt_me_idle_close_by_peer_total 1274
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2520448
telemt_me_route_drop_channel_closed_total 208
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5731951
telemt_me_endpoint_quarantine_total 997
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 967
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
telemt_desync_total 24514
telemt_desync_full_logged_total 8154
telemt_desync_suppressed_total 16360
telemt_desync_frames_bucket_total{bucket="1_2"} 6041
telemt_desync_frames_bucket_total{bucket="3_10"} 9013
telemt_desync_frames_bucket_total{bucket="gt_10"} 9460
telemt_pool_swap_total 138
telemt_pool_force_close_total 3722
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 452
telemt_me_draining_writers_reap_progress_total 43570
telemt_me_writer_removed_unexpected_total 1288
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4155
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40765
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 260
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39848
telemt_me_writer_teardown_success_total{mode="normal"} 44920
telemt_me_writer_teardown_noop_total 43574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88494
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.704339
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88494
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 452
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 1108
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 102
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 5733347
telemt_user_connections_current{user="hello"} 4128
telemt_user_octets_from_client{user="hello"} 105576668561 (98.33 GB)
telemt_user_octets_to_client{user="hello"} 2490958519704 (2.27 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1620
telemt_user_unique_ips_recent_window{user="hello"} 549
```