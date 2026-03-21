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

# Server Metrics 2026-03-21 13:00:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 59081.1 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1936193
telemt_connections_bad_total 97226
telemt_connections_current 1652
telemt_connections_me_current 1652
telemt_handshake_timeouts_total 71495
telemt_upstream_connect_attempt_total 22793
telemt_upstream_connect_success_total 22679
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 22755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1262
telemt_me_reconnect_success_total 520
telemt_me_reader_eof_total 503
telemt_me_idle_close_by_peer_total 503
telemt_me_route_drop_no_conn_total 1458067
telemt_me_route_drop_channel_closed_total 476
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1520999
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 415
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 467
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
telemt_me_writers_active_current 46
telemt_desync_total 5908
telemt_desync_full_logged_total 2065
telemt_desync_suppressed_total 3843
telemt_desync_frames_bucket_total{bucket="1_2"} 1275
telemt_desync_frames_bucket_total{bucket="3_10"} 2265
telemt_desync_frames_bucket_total{bucket="gt_10"} 2368
telemt_pool_swap_total 64
telemt_pool_force_close_total 1874
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 20379
telemt_me_writer_removed_unexpected_total 484
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1682
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19033
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1809
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18505
telemt_me_writer_teardown_success_total{mode="normal"} 20715
telemt_me_writer_teardown_noop_total 20383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41098
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.642903
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41098
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1519880
telemt_user_connections_current{user="hello"} 1652
telemt_user_octets_from_client{user="hello"} 22560291967 (21.01 GB)
telemt_user_octets_to_client{user="hello"} 394133347783 (367.07 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 4726.4 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312820
telemt_connections_bad_total 18033
telemt_connections_current 2235
telemt_connections_me_current 2235
telemt_handshake_timeouts_total 17290
telemt_upstream_connect_attempt_total 2134
telemt_upstream_connect_success_total 2070
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 2116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 193
telemt_me_reconnect_success_total 132
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 243728
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257023
telemt_me_endpoint_quarantine_total 38
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 37
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
telemt_me_writers_active_current 50
telemt_desync_total 926
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 3
telemt_pool_force_close_total 131
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 1745
telemt_me_writer_removed_unexpected_total 127
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 232
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1640
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1614
telemt_me_writer_teardown_success_total{mode="normal"} 1872
telemt_me_writer_teardown_noop_total 1745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.910982
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 121
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 256834
telemt_user_connections_current{user="hello"} 2235
telemt_user_octets_from_client{user="hello"} 4031694424 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 71317746928 (66.42 GB)
telemt_user_unique_ips_current{user="hello"} 1135
telemt_user_unique_ips_recent_window{user="hello"} 834
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 59079.4 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3751811
telemt_connections_bad_total 383263
telemt_connections_current 4844
telemt_connections_me_current 4844
telemt_handshake_timeouts_total 146622
telemt_upstream_connect_attempt_total 22260
telemt_upstream_connect_success_total 22226
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 816
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 463
telemt_me_idle_close_by_peer_total 463
telemt_me_route_drop_no_conn_total 1794624
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3003860
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 453
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
telemt_me_writers_active_current 46
telemt_desync_total 12852
telemt_desync_full_logged_total 4358
telemt_desync_suppressed_total 8494
telemt_desync_frames_bucket_total{bucket="1_2"} 2731
telemt_desync_frames_bucket_total{bucket="3_10"} 5019
telemt_desync_frames_bucket_total{bucket="gt_10"} 5102
telemt_pool_swap_total 63
telemt_pool_force_close_total 1986
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 295
telemt_me_draining_writers_reap_progress_total 20236
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1718
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18786
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18250
telemt_me_writer_teardown_success_total{mode="normal"} 20504
telemt_me_writer_teardown_noop_total 20252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40756
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 58.485319
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40756
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 295
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2999986
telemt_user_connections_current{user="hello"} 4844
telemt_user_octets_from_client{user="hello"} 49097695828 (45.73 GB)
telemt_user_octets_to_client{user="hello"} 1051517409588 (979.30 GB)
telemt_user_unique_ips_current{user="hello"} 1779
telemt_user_unique_ips_recent_window{user="hello"} 853
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 59080.4 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3079071
telemt_connections_bad_total 334211
telemt_connections_current 4321
telemt_connections_me_current 4321
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 120574
telemt_upstream_connect_attempt_total 26971
telemt_upstream_connect_success_total 26698
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 26831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 476
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1144
telemt_me_reconnect_success_total 528
telemt_me_reader_eof_total 490
telemt_me_idle_close_by_peer_total 490
telemt_me_route_drop_no_conn_total 959636
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2212280
telemt_me_endpoint_quarantine_total 391
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 454
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
telemt_me_writers_active_current 44
telemt_desync_total 10218
telemt_desync_full_logged_total 3453
telemt_desync_suppressed_total 6765
telemt_desync_frames_bucket_total{bucket="1_2"} 2540
telemt_desync_frames_bucket_total{bucket="3_10"} 3950
telemt_desync_frames_bucket_total{bucket="gt_10"} 3728
telemt_pool_swap_total 64
telemt_pool_force_close_total 1793
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 19723
telemt_me_writer_removed_unexpected_total 478
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1665
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18556
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1675
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17930
telemt_me_writer_teardown_success_total{mode="normal"} 20221
telemt_me_writer_teardown_noop_total 19724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39945
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.450003
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39945
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2213259
telemt_user_connections_current{user="hello"} 4321
telemt_user_octets_from_client{user="hello"} 41778108449 (38.91 GB)
telemt_user_octets_to_client{user="hello"} 1046509545323 (974.64 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1586
telemt_user_unique_ips_recent_window{user="hello"} 669
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 59044.1 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3009062
telemt_connections_bad_total 328815
telemt_connections_current 3444
telemt_connections_me_current 3444
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 87543
telemt_upstream_connect_attempt_total 32173
telemt_upstream_connect_success_total 31950
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 839
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1270
telemt_me_reconnect_success_total 610
telemt_me_reader_eof_total 554
telemt_me_idle_close_by_peer_total 554
telemt_me_route_drop_no_conn_total 910184
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2186233
telemt_me_endpoint_quarantine_total 435
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 446
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
telemt_me_writers_active_current 47
telemt_desync_total 10072
telemt_desync_full_logged_total 3376
telemt_desync_suppressed_total 6696
telemt_desync_frames_bucket_total{bucket="1_2"} 2599
telemt_desync_frames_bucket_total{bucket="3_10"} 3841
telemt_desync_frames_bucket_total{bucket="gt_10"} 3632
telemt_pool_swap_total 62
telemt_pool_force_close_total 1743
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 204
telemt_me_draining_writers_reap_progress_total 21067
telemt_me_writer_removed_unexpected_total 528
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1782
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19847
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1588
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 155
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19324
telemt_me_writer_teardown_success_total{mode="normal"} 21629
telemt_me_writer_teardown_noop_total 21071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42700
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.311663
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42700
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 204
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 531
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2191325
telemt_user_connections_current{user="hello"} 3445
telemt_user_octets_from_client{user="hello"} 48706857401 (45.36 GB)
telemt_user_octets_to_client{user="hello"} 1042174933124 (970.60 GB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1276
telemt_user_unique_ips_recent_window{user="hello"} 610
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 59083.4 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10022604
telemt_connections_bad_total 675297
telemt_connections_current 6149
telemt_connections_me_current 6149
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 328870
telemt_upstream_connect_attempt_total 89326
telemt_upstream_connect_success_total 84136
telemt_upstream_connect_fail_total 4327
telemt_upstream_connect_attempts_per_request{bucket="1"} 88463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4327
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3487
telemt_me_reconnect_success_total 1182
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 834
telemt_me_route_drop_no_conn_total 18226352
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8265152
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 466
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
telemt_desync_total 15741
telemt_desync_full_logged_total 5025
telemt_desync_suppressed_total 10716
telemt_desync_frames_bucket_total{bucket="1_2"} 3357
telemt_desync_frames_bucket_total{bucket="3_10"} 6943
telemt_desync_frames_bucket_total{bucket="gt_10"} 5441
telemt_pool_swap_total 60
telemt_pool_force_close_total 1906
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 393
telemt_me_draining_writers_reap_progress_total 19258
telemt_me_writer_removed_unexpected_total 1144
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2490
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17795
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1632
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17352
telemt_me_writer_teardown_success_total{mode="normal"} 20285
telemt_me_writer_teardown_noop_total 19267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.337292
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 393
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 822
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 8322816
telemt_user_connections_current{user="hello"} 6149
telemt_user_octets_from_client{user="hello"} 64806943113 (60.36 GB)
telemt_user_octets_to_client{user="hello"} 701241213048 (653.08 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 2094
telemt_user_unique_ips_recent_window{user="hello"} 1249
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 59051.0 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3035787
telemt_connections_bad_total 360098
telemt_connections_current 3911
telemt_connections_me_current 3911
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 66733
telemt_upstream_connect_attempt_total 25295
telemt_upstream_connect_success_total 25015
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 25265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_reconnect_attempts_total 2476
telemt_me_reconnect_success_total 850
telemt_me_reader_eof_total 841
telemt_me_idle_close_by_peer_total 841
telemt_me_route_drop_no_conn_total 1118364
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2301771
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 452
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
telemt_me_writers_active_current 44
telemt_desync_total 10704
telemt_desync_full_logged_total 3735
telemt_desync_suppressed_total 6969
telemt_desync_frames_bucket_total{bucket="1_2"} 2090
telemt_desync_frames_bucket_total{bucket="3_10"} 4277
telemt_desync_frames_bucket_total{bucket="gt_10"} 4337
telemt_pool_swap_total 60
telemt_pool_force_close_total 1687
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 21118
telemt_me_writer_removed_unexpected_total 813
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2024
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19935
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19431
telemt_me_writer_teardown_success_total{mode="normal"} 21959
telemt_me_writer_teardown_noop_total 21119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43078
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.475807
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43078
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 715
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 2286531
telemt_user_connections_current{user="hello"} 3911
telemt_user_octets_from_client{user="hello"} 44423125552 (41.37 GB)
telemt_user_octets_to_client{user="hello"} 1003162781118 (934.27 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1513
telemt_user_unique_ips_recent_window{user="hello"} 638
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 59045.5 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4615169
telemt_connections_bad_total 230796
telemt_connections_current 3677
telemt_connections_me_current 3677
telemt_handshake_timeouts_total 2037141
telemt_upstream_connect_attempt_total 23513
telemt_upstream_connect_success_total 23479
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 23482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 982
telemt_me_reconnect_success_total 420
telemt_me_reader_eof_total 427
telemt_me_idle_close_by_peer_total 427
telemt_me_route_drop_no_conn_total 1004273
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2060687
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 462
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
telemt_desync_total 9783
telemt_desync_full_logged_total 3479
telemt_desync_suppressed_total 6304
telemt_desync_frames_bucket_total{bucket="1_2"} 1798
telemt_desync_frames_bucket_total{bucket="3_10"} 3894
telemt_desync_frames_bucket_total{bucket="gt_10"} 4091
telemt_pool_swap_total 64
telemt_pool_force_close_total 1628
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 21054
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1435
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20055
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19426
telemt_me_writer_teardown_success_total{mode="normal"} 21490
telemt_me_writer_teardown_noop_total 21054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42544
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.398957
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42544
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 365
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2054046
telemt_user_connections_current{user="hello"} 3677
telemt_user_octets_from_client{user="hello"} 37914814356 (35.31 GB)
telemt_user_octets_to_client{user="hello"} 972582306752 (905.79 GB)
telemt_user_unique_ips_current{user="hello"} 1426
telemt_user_unique_ips_recent_window{user="hello"} 671
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 57037.4 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 986478
telemt_connections_bad_total 114381
telemt_connections_current 819
telemt_connections_me_current 819
telemt_handshake_timeouts_total 346937
telemt_upstream_connect_attempt_total 27016
telemt_upstream_connect_success_total 27014
telemt_upstream_connect_attempts_per_request{bucket="1"} 27014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1146
telemt_me_reconnect_success_total 451
telemt_me_reader_eof_total 444
telemt_me_idle_close_by_peer_total 444
telemt_me_route_drop_no_conn_total 204705
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456554
telemt_me_endpoint_quarantine_total 530
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 484
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 3112
telemt_desync_full_logged_total 1164
telemt_desync_suppressed_total 1948
telemt_desync_frames_bucket_total{bucket="1_2"} 541
telemt_desync_frames_bucket_total{bucket="3_10"} 1107
telemt_desync_frames_bucket_total{bucket="gt_10"} 1464
telemt_pool_swap_total 63
telemt_pool_force_close_total 1416
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 24228
telemt_me_writer_removed_unexpected_total 421
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1777
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22880
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1413
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22812
telemt_me_writer_teardown_success_total{mode="normal"} 24657
telemt_me_writer_teardown_noop_total 24228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.177790
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 364
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 456360
telemt_user_connections_current{user="hello"} 819
telemt_user_octets_from_client{user="hello"} 7436608687 (6.93 GB)
telemt_user_octets_to_client{user="hello"} 174081526797 (162.13 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 59055.4 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3265288
telemt_connections_bad_total 315812
telemt_connections_current 4516
telemt_connections_me_current 4516
telemt_handshake_timeouts_total 97002
telemt_upstream_connect_attempt_total 24327
telemt_upstream_connect_success_total 24227
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 24296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12150
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 973
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 894372
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2568429
telemt_me_endpoint_quarantine_total 453
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 457
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
telemt_desync_total 10505
telemt_desync_full_logged_total 3450
telemt_desync_suppressed_total 7055
telemt_desync_frames_bucket_total{bucket="1_2"} 2506
telemt_desync_frames_bucket_total{bucket="3_10"} 3909
telemt_desync_frames_bucket_total{bucket="gt_10"} 4090
telemt_pool_swap_total 65
telemt_pool_force_close_total 1672
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 21867
telemt_me_writer_removed_unexpected_total 505
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1687
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20683
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1642
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20195
telemt_me_writer_teardown_success_total{mode="normal"} 22370
telemt_me_writer_teardown_noop_total 21867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44237
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.585862
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44237
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 490
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2561337
telemt_user_connections_current{user="hello"} 4516
telemt_user_octets_from_client{user="hello"} 54219825360 (50.50 GB)
telemt_user_octets_to_client{user="hello"} 1206662767576 (1.10 TB)
telemt_user_unique_ips_current{user="hello"} 1568
telemt_user_unique_ips_recent_window{user="hello"} 767
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 59052.5 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2942130
telemt_connections_bad_total 244257
telemt_connections_current 4171
telemt_connections_me_current 4171
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 84219
telemt_upstream_connect_attempt_total 40564
telemt_upstream_connect_success_total 40304
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 40519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 586
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_reconnect_attempts_total 3419
telemt_me_reconnect_success_total 731
telemt_me_reader_eof_total 631
telemt_me_idle_close_by_peer_total 631
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 953712
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2364998
telemt_me_endpoint_quarantine_total 510
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 456
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
telemt_desync_total 9152
telemt_desync_full_logged_total 3105
telemt_desync_suppressed_total 6047
telemt_desync_frames_bucket_total{bucket="1_2"} 2359
telemt_desync_frames_bucket_total{bucket="3_10"} 3371
telemt_desync_frames_bucket_total{bucket="gt_10"} 3422
telemt_pool_swap_total 64
telemt_pool_force_close_total 1618
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 21075
telemt_me_writer_removed_unexpected_total 645
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1991
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19757
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1510
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19457
telemt_me_writer_teardown_success_total{mode="normal"} 21748
telemt_me_writer_teardown_noop_total 21076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.607225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2375046
telemt_user_connections_current{user="hello"} 4171
telemt_user_octets_from_client{user="hello"} 44038244097 (41.01 GB)
telemt_user_octets_to_client{user="hello"} 1040502185320 (969.04 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1520
telemt_user_unique_ips_recent_window{user="hello"} 640
```