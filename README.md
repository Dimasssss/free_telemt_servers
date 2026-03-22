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

# Server Metrics 2026-03-22 14:57:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 64286.3 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2187249
telemt_connections_bad_total 108869
telemt_connections_current 1903
telemt_connections_me_current 1903
telemt_handshake_timeouts_total 84445
telemt_upstream_connect_attempt_total 23907
telemt_upstream_connect_success_total 23906
telemt_upstream_connect_attempts_per_request{bucket="1"} 23906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 977
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 403
telemt_me_route_drop_no_conn_total 1724066
telemt_me_route_drop_channel_closed_total 700
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1860184
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 508
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 9365
telemt_desync_full_logged_total 2897
telemt_desync_suppressed_total 6468
telemt_desync_frames_bucket_total{bucket="1_2"} 2579
telemt_desync_frames_bucket_total{bucket="3_10"} 3504
telemt_desync_frames_bucket_total{bucket="gt_10"} 3282
telemt_pool_swap_total 71
telemt_pool_force_close_total 2167
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 21830
telemt_me_writer_removed_unexpected_total 390
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1574
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20467
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2122
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19663
telemt_me_writer_teardown_success_total{mode="normal"} 22041
telemt_me_writer_teardown_noop_total 21834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43875
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 185.747989
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43875
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 352
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1857050
telemt_user_connections_current{user="hello"} 1903
telemt_user_octets_from_client{user="hello"} 28483425292 (26.53 GB)
telemt_user_octets_to_client{user="hello"} 508880221876 (473.93 GB)
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 77652.3 (21h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3446909
telemt_connections_bad_total 311845
telemt_connections_current 2116
telemt_connections_me_current 2116
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 80907
telemt_upstream_connect_attempt_total 49330
telemt_upstream_connect_success_total 48732
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 49261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5633
telemt_me_reconnect_success_total 1941
telemt_me_reader_eof_total 1865
telemt_me_idle_close_by_peer_total 1865
telemt_me_route_drop_no_conn_total 3425768
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2732250
telemt_me_endpoint_quarantine_total 630
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 602
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
telemt_me_writers_active_current 86
telemt_desync_total 10530
telemt_desync_full_logged_total 5837
telemt_desync_suppressed_total 4693
telemt_desync_frames_bucket_total{bucket="1_2"} 2476
telemt_desync_frames_bucket_total{bucket="3_10"} 4164
telemt_desync_frames_bucket_total{bucket="gt_10"} 3890
telemt_pool_swap_total 74
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 185
telemt_me_draining_writers_reap_progress_total 30671
telemt_me_writer_removed_unexpected_total 1823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3581
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28914
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28497
telemt_me_writer_teardown_success_total{mode="normal"} 32495
telemt_me_writer_teardown_noop_total 30671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63166
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.365800
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63166
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 185
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1652
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 2743662
telemt_user_connections_current{user="hello"} 2116
telemt_user_octets_from_client{user="hello"} 33044719691 (30.78 GB)
telemt_user_octets_to_client{user="hello"} 595601919758 (554.70 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1361
telemt_user_unique_ips_recent_window{user="hello"} 720
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 152512.2 (42h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14898081
telemt_connections_bad_total 1345558
telemt_connections_current 4508
telemt_connections_me_current 4508
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 363920
telemt_upstream_connect_attempt_total 69430
telemt_upstream_connect_success_total 69336
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1656
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2540
telemt_me_reconnect_success_total 1323
telemt_me_reader_eof_total 1261
telemt_me_idle_close_by_peer_total 1260
telemt_me_route_drop_no_conn_total 13441044
telemt_me_route_drop_channel_closed_total 133
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11935076
telemt_me_endpoint_quarantine_total 966
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1135
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 48183
telemt_desync_full_logged_total 15164
telemt_desync_suppressed_total 33019
telemt_desync_frames_bucket_total{bucket="1_2"} 10883
telemt_desync_frames_bucket_total{bucket="3_10"} 18884
telemt_desync_frames_bucket_total{bucket="gt_10"} 18416
telemt_pool_swap_total 164
telemt_pool_force_close_total 5596
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 913
telemt_me_draining_writers_reap_progress_total 50204
telemt_me_writer_removed_unexpected_total 1216
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4376
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46349
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5145
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 451
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44608
telemt_me_writer_teardown_success_total{mode="normal"} 50725
telemt_me_writer_teardown_noop_total 50254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100979
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 288.752177
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100979
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 913
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1136
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 11936652
telemt_user_connections_current{user="hello"} 4508
telemt_user_octets_from_client{user="hello"} 167053920921 (155.58 GB)
telemt_user_octets_to_client{user="hello"} 3077098161623 (2.80 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1696
telemt_user_unique_ips_recent_window{user="hello"} 862
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 152513.9 (42h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10802354
telemt_connections_bad_total 1041223
telemt_connections_current 5329
telemt_connections_me_current 5329
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 319776
telemt_upstream_connect_attempt_total 81531
telemt_upstream_connect_success_total 80382
telemt_upstream_connect_fail_total 826
telemt_upstream_connect_attempts_per_request{bucket="1"} 81208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3685
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 826
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3831
telemt_me_reconnect_success_total 1542
telemt_me_reader_eof_total 1416
telemt_me_idle_close_by_peer_total 1416
telemt_me_route_drop_no_conn_total 4279885
telemt_me_route_drop_channel_closed_total 471
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8062864
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1157
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 89
telemt_desync_total 35895
telemt_desync_full_logged_total 12051
telemt_desync_suppressed_total 23844
telemt_desync_frames_bucket_total{bucket="1_2"} 8826
telemt_desync_frames_bucket_total{bucket="3_10"} 13815
telemt_desync_frames_bucket_total{bucket="gt_10"} 13254
telemt_pool_swap_total 162
telemt_pool_force_close_total 5012
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 48392
telemt_me_writer_removed_unexpected_total 1448
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4455
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45242
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 437
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43380
telemt_me_writer_teardown_success_total{mode="normal"} 49697
telemt_me_writer_teardown_noop_total 48407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98104
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 96.675127
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98104
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 1313
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 8001905
telemt_user_connections_current{user="hello"} 5329
telemt_user_octets_from_client{user="hello"} 201667046197 (187.82 GB)
telemt_user_octets_to_client{user="hello"} 3604032141110 (3.28 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2216
telemt_user_unique_ips_recent_window{user="hello"} 628
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 152478.4 (42h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10248431
telemt_connections_bad_total 875514
telemt_connections_current 3523
telemt_connections_me_current 3523
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 327537
telemt_upstream_connect_attempt_total 66897
telemt_upstream_connect_success_total 65974
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31087
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4542
telemt_me_reconnect_success_total 1848
telemt_me_reader_eof_total 1601
telemt_me_idle_close_by_peer_total 1600
telemt_me_route_drop_no_conn_total 5061902
telemt_me_route_drop_channel_closed_total 350
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7738434
telemt_me_endpoint_quarantine_total 1051
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1118
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 35512
telemt_desync_full_logged_total 11763
telemt_desync_suppressed_total 23749
telemt_desync_frames_bucket_total{bucket="1_2"} 8990
telemt_desync_frames_bucket_total{bucket="3_10"} 13591
telemt_desync_frames_bucket_total{bucket="gt_10"} 12931
telemt_pool_swap_total 159
telemt_pool_force_close_total 4990
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 49031
telemt_me_writer_removed_unexpected_total 1745
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4910
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45774
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 533
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44041
telemt_me_writer_teardown_success_total{mode="normal"} 50684
telemt_me_writer_teardown_noop_total 49102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99786
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3168.590620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99786
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1605
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7731740
telemt_user_connections_current{user="hello"} 3523
telemt_user_octets_from_client{user="hello"} 179240336497 (166.93 GB)
telemt_user_octets_to_client{user="hello"} 3208601632321 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1411
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 22757.4 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9627059
telemt_connections_bad_total 598116
telemt_connections_current 6863
telemt_connections_me_current 6863
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 154198
telemt_upstream_connect_attempt_total 29620
telemt_upstream_connect_success_total 28154
telemt_upstream_connect_fail_total 1034
telemt_upstream_connect_attempts_per_request{bucket="1"} 29188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4761
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1034
telemt_me_keepalive_timeout_total 904
telemt_me_reconnect_attempts_total 5526
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 397
telemt_me_idle_close_by_peer_total 397
telemt_me_route_drop_no_conn_total 23780460
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8021972
telemt_me_endpoint_quarantine_total 142
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 173
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
telemt_desync_total 12057
telemt_desync_full_logged_total 3097
telemt_desync_suppressed_total 8960
telemt_desync_frames_bucket_total{bucket="1_2"} 2120
telemt_desync_frames_bucket_total{bucket="3_10"} 4931
telemt_desync_frames_bucket_total{bucket="gt_10"} 5006
telemt_pool_swap_total 21
telemt_pool_force_close_total 888
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 319
telemt_me_draining_writers_reap_progress_total 6054
telemt_me_writer_removed_unexpected_total 516
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1031
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5502
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 620
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 268
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5166
telemt_me_writer_teardown_success_total{mode="normal"} 6533
telemt_me_writer_teardown_noop_total 6059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12592
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.864266
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12592
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 319
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 432
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 8036492
telemt_user_connections_current{user="hello"} 6863
telemt_user_octets_from_client{user="hello"} 46362527535 (43.18 GB)
telemt_user_octets_to_client{user="hello"} 234757119332 (218.63 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2491
telemt_user_unique_ips_recent_window{user="hello"} 1411
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 152484.3 (42h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9968363
telemt_connections_bad_total 826628
telemt_connections_current 5146
telemt_connections_me_current 5146
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 218435
telemt_upstream_connect_attempt_total 91383
telemt_upstream_connect_success_total 90455
telemt_upstream_connect_fail_total 803
telemt_upstream_connect_attempts_per_request{bucket="1"} 91258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 803
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71518
telemt_me_reconnect_success_total 2496
telemt_me_reader_eof_total 2223
telemt_me_idle_close_by_peer_total 2222
telemt_me_route_drop_no_conn_total 4933196
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7872730
telemt_me_endpoint_quarantine_total 1024
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1137
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
telemt_me_writers_active_current 46
telemt_desync_total 40478
telemt_desync_full_logged_total 13882
telemt_desync_suppressed_total 26596
telemt_desync_frames_bucket_total{bucket="1_2"} 8235
telemt_desync_frames_bucket_total{bucket="3_10"} 15689
telemt_desync_frames_bucket_total{bucket="gt_10"} 16554
telemt_pool_swap_total 156
telemt_pool_force_close_total 4652
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 51818
telemt_me_writer_removed_unexpected_total 2249
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5498
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 655
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47166
telemt_me_writer_teardown_success_total{mode="normal"} 54085
telemt_me_writer_teardown_noop_total 51819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105904
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.161895
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105904
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2094
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 7873191
telemt_user_connections_current{user="hello"} 5146
telemt_user_octets_from_client{user="hello"} 179441155879 (167.12 GB)
telemt_user_octets_to_client{user="hello"} 2963944113929 (2.70 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2022
telemt_user_unique_ips_recent_window{user="hello"} 1101
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 89320.1 (24h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10267253
telemt_connections_bad_total 375613
telemt_connections_current 3970
telemt_connections_me_current 3970
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4325200
telemt_upstream_connect_attempt_total 43453
telemt_upstream_connect_success_total 43136
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 43444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_reconnect_attempts_total 47960
telemt_me_reconnect_success_total 1475
telemt_me_reader_eof_total 1140
telemt_me_idle_close_by_peer_total 1139
telemt_me_route_drop_no_conn_total 3818131
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4935595
telemt_me_endpoint_quarantine_total 584
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 672
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 26958
telemt_desync_full_logged_total 9099
telemt_desync_suppressed_total 17859
telemt_desync_frames_bucket_total{bucket="1_2"} 5444
telemt_desync_frames_bucket_total{bucket="3_10"} 10654
telemt_desync_frames_bucket_total{bucket="gt_10"} 10860
telemt_pool_swap_total 94
telemt_pool_force_close_total 2923
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 302
telemt_me_draining_writers_reap_progress_total 30683
telemt_me_writer_removed_unexpected_total 1204
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2786
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29130
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27760
telemt_me_writer_teardown_success_total{mode="normal"} 31916
telemt_me_writer_teardown_noop_total 30690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62606
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.547686
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62606
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 302
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1315
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4929466
telemt_user_connections_current{user="hello"} 3970
telemt_user_octets_from_client{user="hello"} 106501375304 (99.19 GB)
telemt_user_octets_to_client{user="hello"} 1854122802402 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1477
telemt_user_unique_ips_recent_window{user="hello"} 1370
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 70291.0 (19h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 882034
telemt_connections_bad_total 11238
telemt_connections_current 1198
telemt_connections_me_current 1198
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17397
telemt_upstream_connect_attempt_total 35095
telemt_upstream_connect_success_total 35007
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 35079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 470
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1587
telemt_me_reconnect_success_total 671
telemt_me_reader_eof_total 646
telemt_me_idle_close_by_peer_total 646
telemt_me_route_drop_no_conn_total 301994
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 783549
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 582
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
telemt_me_writers_warm_current 38
telemt_desync_total 4329
telemt_desync_full_logged_total 1316
telemt_desync_suppressed_total 3013
telemt_desync_frames_bucket_total{bucket="1_2"} 1024
telemt_desync_frames_bucket_total{bucket="3_10"} 1720
telemt_desync_frames_bucket_total{bucket="gt_10"} 1585
telemt_pool_swap_total 74
telemt_pool_force_close_total 1853
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 28895
telemt_me_writer_removed_unexpected_total 625
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27327
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1775
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27042
telemt_me_writer_teardown_success_total{mode="normal"} 29543
telemt_me_writer_teardown_noop_total 28897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58440
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.321450
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58440
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 573
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 784703
telemt_user_connections_current{user="hello"} 1198
telemt_user_octets_from_client{user="hello"} 14627610013 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 363454463371 (338.49 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 152489.0 (42h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12205418
telemt_connections_bad_total 1422326
telemt_connections_current 5834
telemt_connections_me_current 5834
telemt_handshake_timeouts_total 334866
telemt_upstream_connect_attempt_total 57131
telemt_upstream_connect_success_total 56908
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 57081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 2229
telemt_me_reconnect_success_total 1189
telemt_me_reader_eof_total 1153
telemt_me_idle_close_by_peer_total 1153
telemt_me_route_drop_no_conn_total 3985214
telemt_me_route_drop_channel_closed_total 118
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9207078
telemt_me_endpoint_quarantine_total 1035
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1139
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 37829
telemt_desync_full_logged_total 12370
telemt_desync_suppressed_total 25459
telemt_desync_frames_bucket_total{bucket="1_2"} 9021
telemt_desync_frames_bucket_total{bucket="3_10"} 14020
telemt_desync_frames_bucket_total{bucket="gt_10"} 14788
telemt_pool_swap_total 169
telemt_pool_force_close_total 4678
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 600
telemt_me_draining_writers_reap_progress_total 51458
telemt_me_writer_removed_unexpected_total 1108
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46780
telemt_me_writer_teardown_success_total{mode="normal"} 52597
telemt_me_writer_teardown_noop_total 51460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104057
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.570080
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104057
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 600
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 1043
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 9176642
telemt_user_connections_current{user="hello"} 5834
telemt_user_octets_from_client{user="hello"} 176956611984 (164.80 GB)
telemt_user_octets_to_client{user="hello"} 4077188948276 (3.71 TB)
telemt_user_unique_ips_current{user="hello"} 2059
telemt_user_unique_ips_recent_window{user="hello"} 825
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 152485.9 (42h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10580424
telemt_connections_bad_total 1182625
telemt_connections_current 5691
telemt_connections_me_current 5691
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 273223
telemt_upstream_connect_attempt_total 82761
telemt_upstream_connect_success_total 82142
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 82678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2017
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_reconnect_attempts_total 8798
telemt_me_reconnect_success_total 2017
telemt_me_reader_eof_total 1883
telemt_me_idle_close_by_peer_total 1883
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 5172055
telemt_me_route_drop_channel_closed_total 336
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8169329
telemt_me_endpoint_quarantine_total 1155
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1145
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
telemt_me_writers_active_current 88
telemt_desync_total 37498
telemt_desync_full_logged_total 12116
telemt_desync_suppressed_total 25382
telemt_desync_frames_bucket_total{bucket="1_2"} 9340
telemt_desync_frames_bucket_total{bucket="3_10"} 13978
telemt_desync_frames_bucket_total{bucket="gt_10"} 14180
telemt_pool_swap_total 161
telemt_pool_force_close_total 4504
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 589
telemt_me_draining_writers_reap_progress_total 50732
telemt_me_writer_removed_unexpected_total 1908
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5302
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47405
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4092
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46228
telemt_me_writer_teardown_success_total{mode="normal"} 52707
telemt_me_writer_teardown_noop_total 50737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103444
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.825664
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103444
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 589
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1640
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8175589
telemt_user_connections_current{user="hello"} 5691
telemt_user_octets_from_client{user="hello"} 144126214109 (134.23 GB)
telemt_user_octets_to_client{user="hello"} 3133489593959 (2.85 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2324
telemt_user_unique_ips_recent_window{user="hello"} 744
```