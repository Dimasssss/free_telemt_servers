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

# Server Metrics 2026-03-22 07:52:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 38789.6 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 838182
telemt_connections_bad_total 51928
telemt_connections_current 1459
telemt_connections_me_current 1459
telemt_handshake_timeouts_total 40176
telemt_upstream_connect_attempt_total 15595
telemt_upstream_connect_success_total 15594
telemt_upstream_connect_attempts_per_request{bucket="1"} 15594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 432
telemt_me_reconnect_success_total 243
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 322674
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693659
telemt_me_endpoint_quarantine_total 276
telemt_me_single_endpoint_shadow_rotate_total 314
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
telemt_me_writers_warm_current 32
telemt_desync_total 5519
telemt_desync_full_logged_total 1549
telemt_desync_suppressed_total 3970
telemt_desync_frames_bucket_total{bucket="1_2"} 1730
telemt_desync_frames_bucket_total{bucket="3_10"} 2060
telemt_desync_frames_bucket_total{bucket="gt_10"} 1729
telemt_pool_swap_total 42
telemt_pool_force_close_total 1171
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 14126
telemt_me_writer_removed_unexpected_total 238
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 978
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13340
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12955
telemt_me_writer_teardown_success_total{mode="normal"} 14318
telemt_me_writer_teardown_noop_total 14127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28445
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.386402
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28445
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 692432
telemt_user_connections_current{user="hello"} 1459
telemt_user_octets_from_client{user="hello"} 9580242064 (8.92 GB)
telemt_user_octets_to_client{user="hello"} 236380870692 (220.15 GB)
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 52156.0 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1326278
telemt_connections_bad_total 127573
telemt_connections_current 1531
telemt_connections_me_current 1531
telemt_handshake_timeouts_total 40468
telemt_upstream_connect_attempt_total 27182
telemt_upstream_connect_success_total 26778
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 27130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1993
telemt_me_reconnect_success_total 822
telemt_me_reader_eof_total 711
telemt_me_idle_close_by_peer_total 711
telemt_me_route_drop_no_conn_total 524219
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 998539
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 416
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
telemt_me_writers_active_current 44
telemt_desync_total 4325
telemt_desync_full_logged_total 2534
telemt_desync_suppressed_total 1791
telemt_desync_frames_bucket_total{bucket="1_2"} 922
telemt_desync_frames_bucket_total{bucket="3_10"} 1674
telemt_desync_frames_bucket_total{bucket="gt_10"} 1729
telemt_pool_swap_total 55
telemt_pool_force_close_total 1480
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 21274
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1892
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20052
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19794
telemt_me_writer_teardown_success_total{mode="normal"} 21944
telemt_me_writer_teardown_noop_total 21274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43218
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.903550
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43218
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 624
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 1000202
telemt_user_connections_current{user="hello"} 1531
telemt_user_octets_from_client{user="hello"} 15681783170 (14.60 GB)
telemt_user_octets_to_client{user="hello"} 359108926415 (334.45 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 992
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 127015.8 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9279756
telemt_connections_bad_total 845338
telemt_connections_current 4467
telemt_connections_me_current 4467
telemt_handshake_timeouts_total 285206
telemt_upstream_connect_attempt_total 46820
telemt_upstream_connect_success_total 46740
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1819
telemt_me_reconnect_success_total 929
telemt_me_reader_eof_total 932
telemt_me_idle_close_by_peer_total 932
telemt_me_route_drop_no_conn_total 5060765
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7298441
telemt_me_endpoint_quarantine_total 800
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 952
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
telemt_desync_total 31669
telemt_desync_full_logged_total 10451
telemt_desync_suppressed_total 21218
telemt_desync_frames_bucket_total{bucket="1_2"} 6907
telemt_desync_frames_bucket_total{bucket="3_10"} 12286
telemt_desync_frames_bucket_total{bucket="gt_10"} 12476
telemt_pool_swap_total 138
telemt_pool_force_close_total 4522
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 42716
telemt_me_writer_removed_unexpected_total 896
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3550
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39552
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4245
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38194
telemt_me_writer_teardown_success_total{mode="normal"} 43102
telemt_me_writer_teardown_noop_total 42760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85862
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 180.694701
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85862
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 827
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 7288923
telemt_user_connections_current{user="hello"} 4467
telemt_user_octets_from_client{user="hello"} 122008439020 (113.63 GB)
telemt_user_octets_to_client{user="hello"} 2470840928476 (2.25 TB)
telemt_user_unique_ips_current{user="hello"} 1735
telemt_user_unique_ips_recent_window{user="hello"} 793
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 127017.2 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7624214
telemt_connections_bad_total 677784
telemt_connections_current 2753
telemt_connections_me_current 2753
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 248800
telemt_upstream_connect_attempt_total 52573
telemt_upstream_connect_success_total 52106
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 52346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2792
telemt_me_reconnect_success_total 1042
telemt_me_reader_eof_total 964
telemt_me_idle_close_by_peer_total 964
telemt_me_route_drop_no_conn_total 2557597
telemt_me_route_drop_channel_closed_total 312
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5649556
telemt_me_endpoint_quarantine_total 808
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 981
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
telemt_me_writers_active_current 43
telemt_desync_total 25944
telemt_desync_full_logged_total 8888
telemt_desync_suppressed_total 17056
telemt_desync_frames_bucket_total{bucket="1_2"} 6204
telemt_desync_frames_bucket_total{bucket="3_10"} 10052
telemt_desync_frames_bucket_total{bucket="gt_10"} 9688
telemt_pool_swap_total 139
telemt_pool_force_close_total 4140
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 41151
telemt_me_writer_removed_unexpected_total 989
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3467
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38592
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37011
telemt_me_writer_teardown_success_total{mode="normal"} 42059
telemt_me_writer_teardown_noop_total 41157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83216
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.592836
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83216
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5571951
telemt_user_connections_current{user="hello"} 2753
telemt_user_octets_from_client{user="hello"} 156792931592 (146.02 GB)
telemt_user_octets_to_client{user="hello"} 2685078961068 (2.44 TB)
telemt_user_msgs_from_client{user="hello"} 41825
telemt_user_msgs_to_client{user="hello"} 50380
telemt_user_unique_ips_current{user="hello"} 1111
telemt_user_unique_ips_recent_window{user="hello"} 571
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 126981.2 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7376833
telemt_connections_bad_total 609015
telemt_connections_current 4281
telemt_connections_me_current 4281
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244121
telemt_upstream_connect_attempt_total 57442
telemt_upstream_connect_success_total 56773
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 56920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2738
telemt_me_reconnect_success_total 1190
telemt_me_reader_eof_total 1098
telemt_me_idle_close_by_peer_total 1098
telemt_me_route_drop_no_conn_total 2974649
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5496687
telemt_me_endpoint_quarantine_total 891
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 936
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 33
telemt_desync_total 25624
telemt_desync_full_logged_total 8758
telemt_desync_suppressed_total 16866
telemt_desync_frames_bucket_total{bucket="1_2"} 6202
telemt_desync_frames_bucket_total{bucket="3_10"} 9852
telemt_desync_frames_bucket_total{bucket="gt_10"} 9570
telemt_pool_swap_total 135
telemt_pool_force_close_total 3990
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 458
telemt_me_draining_writers_reap_progress_total 42116
telemt_me_writer_removed_unexpected_total 1108
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3726
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39502
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3692
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 298
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38126
telemt_me_writer_teardown_success_total{mode="normal"} 43228
telemt_me_writer_teardown_noop_total 42128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.858672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 458
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1031
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5490015
telemt_user_connections_current{user="hello"} 4281
telemt_user_octets_from_client{user="hello"} 144872198547 (134.92 GB)
telemt_user_octets_to_client{user="hello"} 2444262985087 (2.22 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1862
telemt_user_unique_ips_recent_window{user="hello"} 580
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 127020.5 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23612956
telemt_connections_bad_total 1955568
telemt_connections_current 5582
telemt_connections_me_current 5582
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 688589
telemt_upstream_connect_attempt_total 241082
telemt_upstream_connect_success_total 221334
telemt_upstream_connect_fail_total 17758
telemt_upstream_connect_attempts_per_request{bucket="1"} 239092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17758
telemt_me_keepalive_timeout_total 414
telemt_me_reconnect_attempts_total 66513
telemt_me_reconnect_success_total 2692
telemt_me_reader_eof_total 1672
telemt_me_idle_close_by_peer_total 1670
telemt_me_route_drop_no_conn_total 45486360
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19058638
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 990
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 998
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
telemt_me_writers_active_current 44
telemt_desync_total 36961
telemt_desync_full_logged_total 10958
telemt_desync_suppressed_total 26003
telemt_desync_frames_bucket_total{bucket="1_2"} 8180
telemt_desync_frames_bucket_total{bucket="3_10"} 16332
telemt_desync_frames_bucket_total{bucket="gt_10"} 12449
telemt_pool_swap_total 132
telemt_pool_force_close_total 4154
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 959
telemt_me_draining_writers_reap_progress_total 39591
telemt_me_writer_removed_unexpected_total 2495
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5363
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36454
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3565
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 589
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35437
telemt_me_writer_teardown_success_total{mode="normal"} 41817
telemt_me_writer_teardown_noop_total 39623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81440
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 283.206074
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81440
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 959
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1821
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 19224317
telemt_user_connections_current{user="hello"} 5582
telemt_user_octets_from_client{user="hello"} 275994035835 (257.04 GB)
telemt_user_octets_to_client{user="hello"} 1423162981527 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2068
telemt_user_unique_ips_recent_window{user="hello"} 1060
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 126988.0 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7009385
telemt_connections_bad_total 640341
telemt_connections_current 4096
telemt_connections_me_current 4096
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 144823
telemt_upstream_connect_attempt_total 65846
telemt_upstream_connect_success_total 65094
telemt_upstream_connect_fail_total 646
telemt_upstream_connect_attempts_per_request{bucket="1"} 65740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 646
telemt_me_reconnect_attempts_total 70106
telemt_me_reconnect_success_total 1941
telemt_me_reader_eof_total 1717
telemt_me_idle_close_by_peer_total 1716
telemt_me_route_drop_no_conn_total 2693035
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5494188
telemt_me_endpoint_quarantine_total 844
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 962
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
telemt_me_writers_warm_current 26
telemt_desync_total 27635
telemt_desync_full_logged_total 9636
telemt_desync_suppressed_total 17999
telemt_desync_frames_bucket_total{bucket="1_2"} 5516
telemt_desync_frames_bucket_total{bucket="3_10"} 10627
telemt_desync_frames_bucket_total{bucket="gt_10"} 11492
telemt_pool_swap_total 132
telemt_pool_force_close_total 3796
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 44292
telemt_me_writer_removed_unexpected_total 1748
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4435
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41642
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3377
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40496
telemt_me_writer_teardown_success_total{mode="normal"} 46077
telemt_me_writer_teardown_noop_total 44293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90370
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.080999
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90370
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 4221
telemt_me_writer_restored_same_endpoint_total 1620
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 5485230
telemt_user_connections_current{user="hello"} 4096
telemt_user_octets_from_client{user="hello"} 138930439776 (129.39 GB)
telemt_user_octets_to_client{user="hello"} 2292934933458 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1717
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 63823.9 (17h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5344667
telemt_connections_bad_total 213764
telemt_connections_current 3524
telemt_connections_me_current 3524
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2127070
telemt_upstream_connect_attempt_total 34730
telemt_upstream_connect_success_total 34488
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 34723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_reconnect_attempts_total 46317
telemt_me_reconnect_success_total 1089
telemt_me_reader_eof_total 781
telemt_me_idle_close_by_peer_total 781
telemt_me_route_drop_no_conn_total 1304444
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2664269
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 489
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 14298
telemt_desync_full_logged_total 4913
telemt_desync_suppressed_total 9385
telemt_desync_frames_bucket_total{bucket="1_2"} 2806
telemt_desync_frames_bucket_total{bucket="3_10"} 5499
telemt_desync_frames_bucket_total{bucket="gt_10"} 5993
telemt_pool_swap_total 69
telemt_pool_force_close_total 2031
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 23042
telemt_me_writer_removed_unexpected_total 851
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21973
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21011
telemt_me_writer_teardown_success_total{mode="normal"} 23915
telemt_me_writer_teardown_noop_total 23044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.281510
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 2627
telemt_me_writer_restored_same_endpoint_total 968
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2665776
telemt_user_connections_current{user="hello"} 3524
telemt_user_octets_from_client{user="hello"} 67514100268 (62.88 GB)
telemt_user_octets_to_client{user="hello"} 1182425001058 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1478
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 44794.6 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363862
telemt_connections_bad_total 2491
telemt_connections_current 830
telemt_connections_me_current 830
telemt_handshake_timeouts_total 7860
telemt_upstream_connect_attempt_total 21285
telemt_upstream_connect_success_total 21231
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 21281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 925
telemt_me_reconnect_success_total 311
telemt_me_reader_eof_total 310
telemt_me_idle_close_by_peer_total 310
telemt_me_route_drop_no_conn_total 112556
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330317
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 387
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
telemt_desync_total 1527
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1092
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 587
telemt_desync_frames_bucket_total{bucket="gt_10"} 457
telemt_pool_swap_total 49
telemt_pool_force_close_total 1112
telemt_me_writer_close_signal_drop_total 41
telemt_me_draining_writers_reap_progress_total 19237
telemt_me_writer_removed_unexpected_total 296
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18280
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1110
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18125
telemt_me_writer_teardown_success_total{mode="normal"} 19547
telemt_me_writer_teardown_noop_total 19237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38784
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.798846
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38784
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 41
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 329757
telemt_user_connections_current{user="hello"} 830
telemt_user_octets_from_client{user="hello"} 5889025264 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 178980089848 (166.69 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 126992.2 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8594059
telemt_connections_bad_total 944589
telemt_connections_current 4575
telemt_connections_me_current 4575
telemt_handshake_timeouts_total 241816
telemt_upstream_connect_attempt_total 49636
telemt_upstream_connect_success_total 49455
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 49597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 1837
telemt_me_reconnect_success_total 999
telemt_me_reader_eof_total 977
telemt_me_idle_close_by_peer_total 977
telemt_me_route_drop_no_conn_total 2405522
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6380392
telemt_me_endpoint_quarantine_total 895
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 965
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
telemt_me_writers_warm_current 37
telemt_desync_total 25512
telemt_desync_full_logged_total 8391
telemt_desync_suppressed_total 17121
telemt_desync_frames_bucket_total{bucket="1_2"} 6324
telemt_desync_frames_bucket_total{bucket="3_10"} 9279
telemt_desync_frames_bucket_total{bucket="gt_10"} 9909
telemt_pool_swap_total 140
telemt_pool_force_close_total 3749
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 449
telemt_me_draining_writers_reap_progress_total 44760
telemt_me_writer_removed_unexpected_total 938
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3534
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42193
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3653
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 96
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41011
telemt_me_writer_teardown_success_total{mode="normal"} 45727
telemt_me_writer_teardown_noop_total 44762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90489
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.547508
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90489
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 449
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 883
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6353897
telemt_user_connections_current{user="hello"} 4575
telemt_user_octets_from_client{user="hello"} 125146987928 (116.55 GB)
telemt_user_octets_to_client{user="hello"} 2980712246788 (2.71 TB)
telemt_user_unique_ips_current{user="hello"} 1785
telemt_user_unique_ips_recent_window{user="hello"} 615
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 126989.0 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7504355
telemt_connections_bad_total 817544
telemt_connections_current 4078
telemt_connections_me_current 4078
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 200951
telemt_upstream_connect_attempt_total 65681
telemt_upstream_connect_success_total 65175
telemt_upstream_connect_fail_total 443
telemt_upstream_connect_attempts_per_request{bucket="1"} 65618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 625
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 443
telemt_me_reconnect_attempts_total 6124
telemt_me_reconnect_success_total 1410
telemt_me_reader_eof_total 1268
telemt_me_idle_close_by_peer_total 1268
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2511239
telemt_me_route_drop_channel_closed_total 207
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5708019
telemt_me_endpoint_quarantine_total 992
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 964
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 31
telemt_desync_total 24430
telemt_desync_full_logged_total 8129
telemt_desync_suppressed_total 16301
telemt_desync_frames_bucket_total{bucket="1_2"} 6031
telemt_desync_frames_bucket_total{bucket="3_10"} 8971
telemt_desync_frames_bucket_total{bucket="gt_10"} 9428
telemt_pool_swap_total 137
telemt_pool_force_close_total 3693
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 43435
telemt_me_writer_removed_unexpected_total 1283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4137
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40642
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39742
telemt_me_writer_teardown_success_total{mode="normal"} 44779
telemt_me_writer_teardown_noop_total 43439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88218
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.607107
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88218
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 272
telemt_me_writer_restored_same_endpoint_total 1105
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 102
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 5709517
telemt_user_connections_current{user="hello"} 4078
telemt_user_octets_from_client{user="hello"} 105227067161 (98.00 GB)
telemt_user_octets_to_client{user="hello"} 2481688592444 (2.26 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1631
telemt_user_unique_ips_recent_window{user="hello"} 566
```