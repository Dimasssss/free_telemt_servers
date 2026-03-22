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

# Server Metrics 2026-03-22 06:05:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 32347.8 (8h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 601189
telemt_connections_bad_total 37700
telemt_connections_current 1583
telemt_connections_me_current 1583
telemt_handshake_timeouts_total 29870
telemt_upstream_connect_attempt_total 13223
telemt_upstream_connect_success_total 13222
telemt_upstream_connect_attempts_per_request{bucket="1"} 13222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 356
telemt_me_reconnect_success_total 206
telemt_me_reader_eof_total 202
telemt_me_idle_close_by_peer_total 202
telemt_me_route_drop_no_conn_total 206017
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497788
telemt_me_endpoint_quarantine_total 239
telemt_me_single_endpoint_shadow_rotate_total 267
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
telemt_me_writers_active_current 45
telemt_desync_total 4215
telemt_desync_full_logged_total 1173
telemt_desync_suppressed_total 3042
telemt_desync_frames_bucket_total{bucket="1_2"} 1399
telemt_desync_frames_bucket_total{bucket="3_10"} 1603
telemt_desync_frames_bucket_total{bucket="gt_10"} 1213
telemt_pool_swap_total 35
telemt_pool_force_close_total 935
telemt_me_writer_close_signal_drop_total 88
telemt_me_draining_writers_reap_progress_total 11962
telemt_me_writer_removed_unexpected_total 199
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 819
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11329
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 925
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11027
telemt_me_writer_teardown_success_total{mode="normal"} 12148
telemt_me_writer_teardown_noop_total 11963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24111
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.024554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24111
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 88
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 187
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 496765
telemt_user_connections_current{user="hello"} 1583
telemt_user_octets_from_client{user="hello"} 6420846004 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 173339927316 (161.44 GB)
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 45714.1 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1053686
telemt_connections_bad_total 93897
telemt_connections_current 1358
telemt_connections_me_current 1358
telemt_handshake_timeouts_total 34847
telemt_upstream_connect_attempt_total 24139
telemt_upstream_connect_success_total 23809
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 24107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_reconnect_attempts_total 1811
telemt_me_reconnect_success_total 657
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 392588
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 806376
telemt_me_endpoint_quarantine_total 420
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 370
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
telemt_desync_total 3400
telemt_desync_full_logged_total 1980
telemt_desync_suppressed_total 1420
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1309
telemt_desync_frames_bucket_total{bucket="gt_10"} 1377
telemt_pool_swap_total 49
telemt_pool_force_close_total 1287
telemt_me_writer_close_signal_drop_total 97
telemt_me_draining_writers_reap_progress_total 18792
telemt_me_writer_removed_unexpected_total 554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1605
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17754
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17505
telemt_me_writer_teardown_success_total{mode="normal"} 19359
telemt_me_writer_teardown_noop_total 18792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38151
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.397340
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38151
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 97
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 495
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 808048
telemt_user_connections_current{user="hello"} 1358
telemt_user_octets_from_client{user="hello"} 13275211719 (12.36 GB)
telemt_user_octets_to_client{user="hello"} 298184725590 (277.71 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 825
telemt_user_unique_ips_recent_window{user="hello"} 412
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 120574.1 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8457998
telemt_connections_bad_total 749513
telemt_connections_current 4236
telemt_connections_me_current 4236
telemt_handshake_timeouts_total 273642
telemt_upstream_connect_attempt_total 44787
telemt_upstream_connect_success_total 44709
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1710
telemt_me_reconnect_success_total 875
telemt_me_reader_eof_total 886
telemt_me_idle_close_by_peer_total 886
telemt_me_route_drop_no_conn_total 4690534
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6755249
telemt_me_endpoint_quarantine_total 764
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 906
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 28709
telemt_desync_full_logged_total 9550
telemt_desync_suppressed_total 19159
telemt_desync_frames_bucket_total{bucket="1_2"} 6222
telemt_desync_frames_bucket_total{bucket="3_10"} 11199
telemt_desync_frames_bucket_total{bucket="gt_10"} 11288
telemt_pool_swap_total 130
telemt_pool_force_close_total 4293
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 648
telemt_me_draining_writers_reap_progress_total 40891
telemt_me_writer_removed_unexpected_total 854
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37871
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4044
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 249
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36598
telemt_me_writer_teardown_success_total{mode="normal"} 41249
telemt_me_writer_teardown_noop_total 40935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82184
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 169.522793
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82184
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 648
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 782
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 6746491
telemt_user_connections_current{user="hello"} 4236
telemt_user_octets_from_client{user="hello"} 114928985380 (107.04 GB)
telemt_user_octets_to_client{user="hello"} 2300846616060 (2.09 TB)
telemt_user_unique_ips_current{user="hello"} 1691
telemt_user_unique_ips_recent_window{user="hello"} 627
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 120575.4 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6976222
telemt_connections_bad_total 621944
telemt_connections_current 3841
telemt_connections_me_current 3841
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 232609
telemt_upstream_connect_attempt_total 48727
telemt_upstream_connect_success_total 48325
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 48530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2060
telemt_me_reconnect_success_total 936
telemt_me_reader_eof_total 915
telemt_me_idle_close_by_peer_total 915
telemt_me_route_drop_no_conn_total 2375645
telemt_me_route_drop_channel_closed_total 289
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5195740
telemt_me_endpoint_quarantine_total 761
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 928
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
telemt_me_writers_active_current 45
telemt_desync_total 24000
telemt_desync_full_logged_total 8258
telemt_desync_suppressed_total 15742
telemt_desync_frames_bucket_total{bucket="1_2"} 5748
telemt_desync_frames_bucket_total{bucket="3_10"} 9326
telemt_desync_frames_bucket_total{bucket="gt_10"} 8926
telemt_pool_swap_total 131
telemt_pool_force_close_total 3898
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 39308
telemt_me_writer_removed_unexpected_total 893
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3240
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36889
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35410
telemt_me_writer_teardown_success_total{mode="normal"} 40129
telemt_me_writer_teardown_noop_total 39314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79443
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.280286
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79443
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 817
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5117050
telemt_user_connections_current{user="hello"} 3841
telemt_user_octets_from_client{user="hello"} 148102000633 (137.93 GB)
telemt_user_octets_to_client{user="hello"} 2458889026171 (2.24 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1494
telemt_user_unique_ips_recent_window{user="hello"} 585
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 120540.1 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6789598
telemt_connections_bad_total 570072
telemt_connections_current 3574
telemt_connections_me_current 3574
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 227784
telemt_upstream_connect_attempt_total 55166
telemt_upstream_connect_success_total 54579
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 54723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2530
telemt_me_reconnect_success_total 1094
telemt_me_reader_eof_total 1025
telemt_me_idle_close_by_peer_total 1025
telemt_me_route_drop_no_conn_total 2436412
telemt_me_route_drop_channel_closed_total 153
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5051201
telemt_me_endpoint_quarantine_total 856
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 894
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 23934
telemt_desync_full_logged_total 8134
telemt_desync_suppressed_total 15800
telemt_desync_frames_bucket_total{bucket="1_2"} 5812
telemt_desync_frames_bucket_total{bucket="3_10"} 9182
telemt_desync_frames_bucket_total{bucket="gt_10"} 8940
telemt_pool_swap_total 129
telemt_pool_force_close_total 3764
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 40270
telemt_me_writer_removed_unexpected_total 1015
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3489
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37812
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3517
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36506
telemt_me_writer_teardown_success_total{mode="normal"} 41301
telemt_me_writer_teardown_noop_total 40282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81583
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.048897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81583
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 950
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 5045506
telemt_user_connections_current{user="hello"} 3574
telemt_user_octets_from_client{user="hello"} 138826128975 (129.29 GB)
telemt_user_octets_to_client{user="hello"} 2296711082727 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1273
telemt_user_unique_ips_recent_window{user="hello"} 580
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 120578.8 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21666927
telemt_connections_bad_total 1838112
telemt_connections_current 5013
telemt_connections_me_current 5013
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 658003
telemt_upstream_connect_attempt_total 211028
telemt_upstream_connect_success_total 192342
telemt_upstream_connect_fail_total 16763
telemt_upstream_connect_attempts_per_request{bucket="1"} 209105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9879
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16763
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65508
telemt_me_reconnect_success_total 2557
telemt_me_reader_eof_total 1601
telemt_me_idle_close_by_peer_total 1600
telemt_me_route_drop_no_conn_total 40970784
telemt_me_route_drop_channel_closed_total 131
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17417471
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 936
telemt_me_single_endpoint_outage_enter_total 153
telemt_me_single_endpoint_outage_exit_total 153
telemt_me_single_endpoint_outage_reconnect_attempt_total 322
telemt_me_single_endpoint_outage_reconnect_success_total 80
telemt_me_single_endpoint_quarantine_bypass_total 322
telemt_me_single_endpoint_shadow_rotate_total 946
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
telemt_me_writers_active_current 45
telemt_desync_total 33631
telemt_desync_full_logged_total 10113
telemt_desync_suppressed_total 23518
telemt_desync_frames_bucket_total{bucket="1_2"} 7393
telemt_desync_frames_bucket_total{bucket="3_10"} 14916
telemt_desync_frames_bucket_total{bucket="gt_10"} 11322
telemt_pool_swap_total 124
telemt_pool_force_close_total 3977
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 879
telemt_me_draining_writers_reap_progress_total 37882
telemt_me_writer_removed_unexpected_total 2379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34893
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 561
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33905
telemt_me_writer_teardown_success_total{mode="normal"} 40010
telemt_me_writer_teardown_noop_total 37909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77919
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 219.259170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77919
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 879
telemt_me_refill_failed_total 3814
telemt_me_writer_restored_same_endpoint_total 1739
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 17556761
telemt_user_connections_current{user="hello"} 5013
telemt_user_octets_from_client{user="hello"} 259450554781 (241.63 GB)
telemt_user_octets_to_client{user="hello"} 1353918657675 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 409002
telemt_user_msgs_to_client{user="hello"} 794272
telemt_user_unique_ips_current{user="hello"} 1838
telemt_user_unique_ips_recent_window{user="hello"} 988
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 120546.3 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6537854
telemt_connections_bad_total 616879
telemt_connections_current 3398
telemt_connections_me_current 3398
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 136982
telemt_upstream_connect_attempt_total 63798
telemt_upstream_connect_success_total 63061
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 63692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_reconnect_attempts_total 69948
telemt_me_reconnect_success_total 1902
telemt_me_reader_eof_total 1677
telemt_me_idle_close_by_peer_total 1676
telemt_me_route_drop_no_conn_total 2510189
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5094195
telemt_me_endpoint_quarantine_total 811
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 915
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
telemt_me_writers_active_current 45
telemt_desync_total 25299
telemt_desync_full_logged_total 8861
telemt_desync_suppressed_total 16438
telemt_desync_frames_bucket_total{bucket="1_2"} 5010
telemt_desync_frames_bucket_total{bucket="3_10"} 9756
telemt_desync_frames_bucket_total{bucket="gt_10"} 10533
telemt_pool_swap_total 125
telemt_pool_force_close_total 3580
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 422
telemt_me_draining_writers_reap_progress_total 42469
telemt_me_writer_removed_unexpected_total 1710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4271
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39943
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3174
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38889
telemt_me_writer_teardown_success_total{mode="normal"} 44214
telemt_me_writer_teardown_noop_total 42470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86684
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.641231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86684
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 422
telemt_me_refill_failed_total 4215
telemt_me_writer_restored_same_endpoint_total 1588
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 5086113
telemt_user_connections_current{user="hello"} 3398
telemt_user_octets_from_client{user="hello"} 130950295752 (121.96 GB)
telemt_user_octets_to_client{user="hello"} 2122465261226 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1418
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 57382.2 (15h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4606795
telemt_connections_bad_total 191397
telemt_connections_current 3219
telemt_connections_me_current 3219
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1820597
telemt_upstream_connect_attempt_total 32628
telemt_upstream_connect_success_total 32411
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 32621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_reconnect_attempts_total 46108
telemt_me_reconnect_success_total 1042
telemt_me_reader_eof_total 733
telemt_me_idle_close_by_peer_total 733
telemt_me_route_drop_no_conn_total 1144473
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2284654
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 444
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
telemt_desync_total 12217
telemt_desync_full_logged_total 4202
telemt_desync_suppressed_total 8015
telemt_desync_frames_bucket_total{bucket="1_2"} 2353
telemt_desync_frames_bucket_total{bucket="3_10"} 4671
telemt_desync_frames_bucket_total{bucket="gt_10"} 5193
telemt_pool_swap_total 62
telemt_pool_force_close_total 1820
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 21176
telemt_me_writer_removed_unexpected_total 803
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1798
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20211
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19356
telemt_me_writer_teardown_success_total{mode="normal"} 22009
telemt_me_writer_teardown_noop_total 21178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43187
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.707289
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43187
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 2618
telemt_me_writer_restored_same_endpoint_total 930
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2286870
telemt_user_connections_current{user="hello"} 3219
telemt_user_octets_from_client{user="hello"} 60391620880 (56.24 GB)
telemt_user_octets_to_client{user="hello"} 1011668859030 (942.19 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1310
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 38353.3 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278770
telemt_connections_bad_total 2013
telemt_connections_current 694
telemt_connections_me_current 694
telemt_handshake_timeouts_total 6844
telemt_upstream_connect_attempt_total 18459
telemt_upstream_connect_success_total 18414
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 18455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 480
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 79600
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249994
telemt_me_endpoint_quarantine_total 364
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 333
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
telemt_me_writers_active_current 44
telemt_desync_total 1275
telemt_desync_full_logged_total 353
telemt_desync_suppressed_total 922
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 42
telemt_pool_force_close_total 936
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 16736
telemt_me_writer_removed_unexpected_total 241
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1067
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15921
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 934
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15800
telemt_me_writer_teardown_success_total{mode="normal"} 16988
telemt_me_writer_teardown_noop_total 16736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33724
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.307399
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33724
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 217
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 249593
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 4176888312 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 149845724076 (139.55 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 120550.6 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7927432
telemt_connections_bad_total 798240
telemt_connections_current 3877
telemt_connections_me_current 3877
telemt_handshake_timeouts_total 224706
telemt_upstream_connect_attempt_total 47432
telemt_upstream_connect_success_total 47261
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 47395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 1703
telemt_me_reconnect_success_total 920
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 913
telemt_me_route_drop_no_conn_total 2243460
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5912124
telemt_me_endpoint_quarantine_total 858
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 924
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
telemt_desync_total 23217
telemt_desync_full_logged_total 7648
telemt_desync_suppressed_total 15569
telemt_desync_frames_bucket_total{bucket="1_2"} 5807
telemt_desync_frames_bucket_total{bucket="3_10"} 8459
telemt_desync_frames_bucket_total{bucket="gt_10"} 8951
telemt_pool_swap_total 133
telemt_pool_force_close_total 3543
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 42822
telemt_me_writer_removed_unexpected_total 876
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3343
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40382
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3455
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39279
telemt_me_writer_teardown_success_total{mode="normal"} 43725
telemt_me_writer_teardown_noop_total 42824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.036527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86549
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 5886570
telemt_user_connections_current{user="hello"} 3877
telemt_user_octets_from_client{user="hello"} 115636097288 (107.69 GB)
telemt_user_octets_to_client{user="hello"} 2761182999328 (2.51 TB)
telemt_user_unique_ips_current{user="hello"} 1459
telemt_user_unique_ips_recent_window{user="hello"} 624
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 120547.4 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6891735
telemt_connections_bad_total 670463
telemt_connections_current 3745
telemt_connections_me_current 3745
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 185838
telemt_upstream_connect_attempt_total 63232
telemt_upstream_connect_success_total 62749
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 63169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_reconnect_attempts_total 5854
telemt_me_reconnect_success_total 1303
telemt_me_reader_eof_total 1170
telemt_me_idle_close_by_peer_total 1170
telemt_me_seq_mismatch_total 57
telemt_me_route_drop_no_conn_total 2300569
telemt_me_route_drop_channel_closed_total 192
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5279948
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 922
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
telemt_desync_total 22108
telemt_desync_full_logged_total 7352
telemt_desync_suppressed_total 14756
telemt_desync_frames_bucket_total{bucket="1_2"} 5544
telemt_desync_frames_bucket_total{bucket="3_10"} 8084
telemt_desync_frames_bucket_total{bucket="gt_10"} 8480
telemt_pool_swap_total 131
telemt_pool_force_close_total 3491
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 41328
telemt_me_writer_removed_unexpected_total 1183
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3903
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38667
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 224
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37837
telemt_me_writer_teardown_success_total{mode="normal"} 42570
telemt_me_writer_teardown_noop_total 41332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83902
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.894715
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83902
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 1014
telemt_me_writer_restored_fallback_total 76
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5282417
telemt_user_connections_current{user="hello"} 3745
telemt_user_octets_from_client{user="hello"} 98853567449 (92.06 GB)
telemt_user_octets_to_client{user="hello"} 2294093581260 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1484
telemt_user_unique_ips_recent_window{user="hello"} 561
```