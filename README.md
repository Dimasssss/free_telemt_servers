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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 12:40:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 57857.1 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1887944
telemt_connections_bad_total 92871
telemt_connections_current 1455
telemt_connections_me_current 1455
telemt_handshake_timeouts_total 70759
telemt_upstream_connect_attempt_total 22426
telemt_upstream_connect_success_total 22315
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 22388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1238
telemt_me_reconnect_success_total 515
telemt_me_reader_eof_total 498
telemt_me_idle_close_by_peer_total 498
telemt_me_route_drop_no_conn_total 1442644
telemt_me_route_drop_channel_closed_total 465
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1481078
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 460
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 5727
telemt_desync_full_logged_total 2004
telemt_desync_suppressed_total 3723
telemt_desync_frames_bucket_total{bucket="1_2"} 1235
telemt_desync_frames_bucket_total{bucket="3_10"} 2206
telemt_desync_frames_bucket_total{bucket="gt_10"} 2286
telemt_pool_swap_total 63
telemt_pool_force_close_total 1849
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 357
telemt_me_draining_writers_reap_progress_total 20051
telemt_me_writer_removed_unexpected_total 479
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1660
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18722
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1784
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18202
telemt_me_writer_teardown_success_total{mode="normal"} 20382
telemt_me_writer_teardown_noop_total 20055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40437
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 154.386020
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40437
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 357
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 446
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1479979
telemt_user_connections_current{user="hello"} 1455
telemt_user_octets_from_client{user="hello"} 21776381843 (20.28 GB)
telemt_user_octets_to_client{user="hello"} 383362667283 (357.03 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3502.1 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239689
telemt_connections_bad_total 14972
telemt_connections_current 2106
telemt_connections_me_current 2106
telemt_handshake_timeouts_total 14260
telemt_upstream_connect_attempt_total 1378
telemt_upstream_connect_success_total 1332
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 90
telemt_me_reconnect_success_total 61
telemt_me_reader_eof_total 58
telemt_me_idle_close_by_peer_total 58
telemt_me_route_drop_no_conn_total 204501
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193583
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 25
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 715
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 386
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 2
telemt_pool_force_close_total 80
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 1103
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 138
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1031
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1023
telemt_me_writer_teardown_success_total{mode="normal"} 1169
telemt_me_writer_teardown_noop_total 1103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2272
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.205622
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2272
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 193487
telemt_user_connections_current{user="hello"} 2106
telemt_user_octets_from_client{user="hello"} 3052484408 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 48249578972 (44.94 GB)
telemt_user_unique_ips_current{user="hello"} 1132
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 57855.4 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3630874
telemt_connections_bad_total 375435
telemt_connections_current 3445
telemt_connections_me_current 3445
telemt_handshake_timeouts_total 143144
telemt_upstream_connect_attempt_total 21923
telemt_upstream_connect_success_total 21890
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 812
telemt_me_reconnect_success_total 451
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 1736801
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2898716
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 444
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 12408
telemt_desync_full_logged_total 4191
telemt_desync_suppressed_total 8217
telemt_desync_frames_bucket_total{bucket="1_2"} 2628
telemt_desync_frames_bucket_total{bucket="3_10"} 4856
telemt_desync_frames_bucket_total{bucket="gt_10"} 4924
telemt_pool_swap_total 62
telemt_pool_force_close_total 1956
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 285
telemt_me_draining_writers_reap_progress_total 19926
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1684
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18507
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1815
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17970
telemt_me_writer_teardown_success_total{mode="normal"} 20191
telemt_me_writer_teardown_noop_total 19942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40133
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.893649
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40133
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 285
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 407
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2894892
telemt_user_connections_current{user="hello"} 3445
telemt_user_octets_from_client{user="hello"} 47030853144 (43.80 GB)
telemt_user_octets_to_client{user="hello"} 1019720130036 (949.69 GB)
telemt_user_unique_ips_current{user="hello"} 1226
telemt_user_unique_ips_recent_window{user="hello"} 529
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 57856.3 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2973263
telemt_connections_bad_total 325481
telemt_connections_current 3646
telemt_connections_me_current 3646
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 117804
telemt_upstream_connect_attempt_total 26643
telemt_upstream_connect_success_total 26371
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 26503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 475
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1138
telemt_me_reconnect_success_total 523
telemt_me_reader_eof_total 485
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 929430
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2125890
telemt_me_endpoint_quarantine_total 389
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 446
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
telemt_me_writers_active_current 43
telemt_desync_total 9690
telemt_desync_full_logged_total 3300
telemt_desync_suppressed_total 6390
telemt_desync_frames_bucket_total{bucket="1_2"} 2427
telemt_desync_frames_bucket_total{bucket="3_10"} 3766
telemt_desync_frames_bucket_total{bucket="gt_10"} 3497
telemt_pool_swap_total 63
telemt_pool_force_close_total 1764
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 19434
telemt_me_writer_removed_unexpected_total 473
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1648
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18279
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1647
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17670
telemt_me_writer_teardown_success_total{mode="normal"} 19927
telemt_me_writer_teardown_noop_total 19435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.125694
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2126948
telemt_user_connections_current{user="hello"} 3646
telemt_user_octets_from_client{user="hello"} 39953303389 (37.21 GB)
telemt_user_octets_to_client{user="hello"} 1007014389003 (937.86 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1350
telemt_user_unique_ips_recent_window{user="hello"} 582
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 57820.0 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2889332
telemt_connections_bad_total 321684
telemt_connections_current 3276
telemt_connections_me_current 3276
telemt_handshake_timeouts_total 85144
telemt_upstream_connect_attempt_total 23290
telemt_upstream_connect_success_total 23200
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 938
telemt_me_reconnect_success_total 597
telemt_me_reader_eof_total 546
telemt_me_idle_close_by_peer_total 546
telemt_me_route_drop_no_conn_total 877295
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2106329
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 437
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 9786
telemt_desync_full_logged_total 3275
telemt_desync_suppressed_total 6511
telemt_desync_frames_bucket_total{bucket="1_2"} 2543
telemt_desync_frames_bucket_total{bucket="3_10"} 3719
telemt_desync_frames_bucket_total{bucket="gt_10"} 3524
telemt_pool_swap_total 61
telemt_pool_force_close_total 1740
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 20738
telemt_me_writer_removed_unexpected_total 521
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1740
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19557
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1588
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 152
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18998
telemt_me_writer_teardown_success_total{mode="normal"} 21297
telemt_me_writer_teardown_noop_total 20742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42039
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.158219
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42039
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 521
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 2103135
telemt_user_connections_current{user="hello"} 3276
telemt_user_octets_from_client{user="hello"} 47484338508 (44.22 GB)
telemt_user_octets_to_client{user="hello"} 1008077584696 (938.85 GB)
telemt_user_unique_ips_current{user="hello"} 1186
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 57859.3 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9564499
telemt_connections_bad_total 654815
telemt_connections_current 5203
telemt_connections_me_current 5203
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 319860
telemt_upstream_connect_attempt_total 88993
telemt_upstream_connect_success_total 83820
telemt_upstream_connect_fail_total 4324
telemt_upstream_connect_attempts_per_request{bucket="1"} 88144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4324
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3482
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 829
telemt_me_idle_close_by_peer_total 828
telemt_me_route_drop_no_conn_total 17134793
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7876641
telemt_me_endpoint_quarantine_total 448
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 457
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
telemt_desync_total 15041
telemt_desync_full_logged_total 4838
telemt_desync_suppressed_total 10203
telemt_desync_frames_bucket_total{bucket="1_2"} 3202
telemt_desync_frames_bucket_total{bucket="3_10"} 6666
telemt_desync_frames_bucket_total{bucket="gt_10"} 5173
telemt_pool_swap_total 59
telemt_pool_force_close_total 1874
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 18972
telemt_me_writer_removed_unexpected_total 1139
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17530
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1603
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 271
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17098
telemt_me_writer_teardown_success_total{mode="normal"} 19993
telemt_me_writer_teardown_noop_total 18981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38974
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.439195
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38974
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 818
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 7934382
telemt_user_connections_current{user="hello"} 5203
telemt_user_octets_from_client{user="hello"} 62196850757 (57.93 GB)
telemt_user_octets_to_client{user="hello"} 688821073112 (641.51 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1859
telemt_user_unique_ips_recent_window{user="hello"} 1085
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 57827.1 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2933766
telemt_connections_bad_total 348838
telemt_connections_current 2904
telemt_connections_me_current 2904
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 64252
telemt_upstream_connect_attempt_total 24903
telemt_upstream_connect_success_total 24623
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 24873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_reconnect_attempts_total 2417
telemt_me_reconnect_success_total 846
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 835
telemt_me_route_drop_no_conn_total 1059804
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2219893
telemt_me_endpoint_quarantine_total 369
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 443
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
telemt_me_writers_active_current 48
telemt_desync_total 10209
telemt_desync_full_logged_total 3593
telemt_desync_suppressed_total 6616
telemt_desync_frames_bucket_total{bucket="1_2"} 1997
telemt_desync_frames_bucket_total{bucket="3_10"} 4091
telemt_desync_frames_bucket_total{bucket="gt_10"} 4121
telemt_pool_swap_total 59
telemt_pool_force_close_total 1659
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 151
telemt_me_draining_writers_reap_progress_total 20743
telemt_me_writer_removed_unexpected_total 808
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1472
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 187
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19084
telemt_me_writer_teardown_success_total{mode="normal"} 21578
telemt_me_writer_teardown_noop_total 20744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42322
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.390934
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42322
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 151
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 713
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 2204779
telemt_user_connections_current{user="hello"} 2904
telemt_user_octets_from_client{user="hello"} 41309951140 (38.47 GB)
telemt_user_octets_to_client{user="hello"} 970978038102 (904.29 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1080
telemt_user_unique_ips_recent_window{user="hello"} 826
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 57821.4 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4433437
telemt_connections_bad_total 226095
telemt_connections_current 2951
telemt_connections_me_current 2951
telemt_handshake_timeouts_total 1944434
telemt_upstream_connect_attempt_total 23127
telemt_upstream_connect_success_total 23093
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 23096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 938
telemt_me_reconnect_success_total 413
telemt_me_reader_eof_total 419
telemt_me_idle_close_by_peer_total 419
telemt_me_route_drop_no_conn_total 963309
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1983928
telemt_me_endpoint_quarantine_total 440
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 453
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
telemt_me_writers_active_current 44
telemt_desync_total 9453
telemt_desync_full_logged_total 3366
telemt_desync_suppressed_total 6087
telemt_desync_frames_bucket_total{bucket="1_2"} 1735
telemt_desync_frames_bucket_total{bucket="3_10"} 3771
telemt_desync_frames_bucket_total{bucket="gt_10"} 3947
telemt_pool_swap_total 63
telemt_pool_force_close_total 1601
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 20700
telemt_me_writer_removed_unexpected_total 403
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1413
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19715
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1546
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19099
telemt_me_writer_teardown_success_total{mode="normal"} 21128
telemt_me_writer_teardown_noop_total 20700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41828
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.228262
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41828
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1977368
telemt_user_connections_current{user="hello"} 2950
telemt_user_octets_from_client{user="hello"} 36328599756 (33.83 GB)
telemt_user_octets_to_client{user="hello"} 938670436444 (874.20 GB)
telemt_user_unique_ips_current{user="hello"} 1100
telemt_user_unique_ips_recent_window{user="hello"} 842
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 55812.7 (15h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937316
telemt_connections_bad_total 95809
telemt_connections_current 717
telemt_connections_me_current 717
telemt_handshake_timeouts_total 334688
telemt_upstream_connect_attempt_total 26447
telemt_upstream_connect_success_total 26445
telemt_upstream_connect_attempts_per_request{bucket="1"} 26445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1118
telemt_me_reconnect_success_total 433
telemt_me_reader_eof_total 432
telemt_me_idle_close_by_peer_total 432
telemt_me_route_drop_no_conn_total 196091
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441567
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 3054
telemt_desync_full_logged_total 1144
telemt_desync_suppressed_total 1910
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 1091
telemt_desync_frames_bucket_total{bucket="gt_10"} 1429
telemt_pool_swap_total 61
telemt_pool_force_close_total 1368
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 94
telemt_me_draining_writers_reap_progress_total 23702
telemt_me_writer_removed_unexpected_total 409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1723
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22396
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1365
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22334
telemt_me_writer_teardown_success_total{mode="normal"} 24119
telemt_me_writer_teardown_noop_total 23702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47821
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.861325
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47821
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 94
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 353
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 441403
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 7101459719 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 167907995801 (156.38 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 57831.2 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3150859
telemt_connections_bad_total 309172
telemt_connections_current 4270
telemt_connections_me_current 4270
telemt_handshake_timeouts_total 91524
telemt_upstream_connect_attempt_total 23972
telemt_upstream_connect_success_total 23872
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 23941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 970
telemt_me_reconnect_success_total 547
telemt_me_reader_eof_total 511
telemt_me_idle_close_by_peer_total 511
telemt_me_route_drop_no_conn_total 855578
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2474151
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 449
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
telemt_me_writers_active_current 43
telemt_desync_total 10078
telemt_desync_full_logged_total 3311
telemt_desync_suppressed_total 6767
telemt_desync_frames_bucket_total{bucket="1_2"} 2405
telemt_desync_frames_bucket_total{bucket="3_10"} 3772
telemt_desync_frames_bucket_total{bucket="gt_10"} 3901
telemt_pool_swap_total 64
telemt_pool_force_close_total 1626
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 21533
telemt_me_writer_removed_unexpected_total 502
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1669
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20383
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1596
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19907
telemt_me_writer_teardown_success_total{mode="normal"} 22052
telemt_me_writer_teardown_noop_total 21533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.465211
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 487
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2467107
telemt_user_connections_current{user="hello"} 4270
telemt_user_octets_from_client{user="hello"} 52083496188 (48.51 GB)
telemt_user_octets_to_client{user="hello"} 1157773370628 (1.05 TB)
telemt_user_unique_ips_current{user="hello"} 1433
telemt_user_unique_ips_recent_window{user="hello"} 774
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 57828.0 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2839332
telemt_connections_bad_total 236727
telemt_connections_current 3497
telemt_connections_me_current 3497
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 79033
telemt_upstream_connect_attempt_total 40110
telemt_upstream_connect_success_total 39851
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 40066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 586
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_reconnect_attempts_total 3410
telemt_me_reconnect_success_total 721
telemt_me_reader_eof_total 624
telemt_me_idle_close_by_peer_total 624
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 918351
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2283018
telemt_me_endpoint_quarantine_total 503
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 448
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 8747
telemt_desync_full_logged_total 2994
telemt_desync_suppressed_total 5753
telemt_desync_frames_bucket_total{bucket="1_2"} 2254
telemt_desync_frames_bucket_total{bucket="3_10"} 3235
telemt_desync_frames_bucket_total{bucket="gt_10"} 3258
telemt_pool_swap_total 63
telemt_pool_force_close_total 1587
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 20649
telemt_me_writer_removed_unexpected_total 637
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1957
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19357
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1483
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 104
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19062
telemt_me_writer_teardown_success_total{mode="normal"} 21314
telemt_me_writer_teardown_noop_total 20650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41964
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.523829
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41964
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2293223
telemt_user_connections_current{user="hello"} 3497
telemt_user_octets_from_client{user="hello"} 42821017405 (39.88 GB)
telemt_user_octets_to_client{user="hello"} 1004072622628 (935.12 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1250
telemt_user_unique_ips_recent_window{user="hello"} 756
```