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

# Server Metrics 2026-03-22 01:14:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 14872.1 (4h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217624
telemt_connections_bad_total 15332
telemt_connections_current 685
telemt_connections_me_current 685
telemt_handshake_timeouts_total 12548
telemt_upstream_connect_attempt_total 6209
telemt_upstream_connect_success_total 6208
telemt_upstream_connect_attempts_per_request{bucket="1"} 6208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 213
telemt_me_reconnect_success_total 104
telemt_me_reader_eof_total 100
telemt_me_idle_close_by_peer_total 100
telemt_me_route_drop_no_conn_total 41122
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177545
telemt_me_endpoint_quarantine_total 115
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 46
telemt_desync_total 1470
telemt_desync_full_logged_total 404
telemt_desync_suppressed_total 1066
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 532
telemt_desync_frames_bucket_total{bucket="gt_10"} 495
telemt_pool_swap_total 16
telemt_pool_force_close_total 418
telemt_me_writer_close_signal_drop_total 29
telemt_me_draining_writers_reap_progress_total 5542
telemt_me_writer_removed_unexpected_total 102
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 402
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5230
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5124
telemt_me_writer_teardown_success_total{mode="normal"} 5632
telemt_me_writer_teardown_noop_total 5543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11175
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.846663
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11175
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 29
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 177254
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 1960776728 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 58475264232 (54.46 GB)
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 28238.3 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 725898
telemt_connections_bad_total 41742
telemt_connections_current 329
telemt_connections_me_current 329
telemt_handshake_timeouts_total 27197
telemt_upstream_connect_attempt_total 12437
telemt_upstream_connect_success_total 12230
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 12416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_reconnect_attempts_total 1081
telemt_me_reconnect_success_total 361
telemt_me_reader_eof_total 313
telemt_me_idle_close_by_peer_total 313
telemt_me_route_drop_no_conn_total 333245
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 582866
telemt_me_endpoint_quarantine_total 263
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 231
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 2545
telemt_desync_full_logged_total 1458
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 951
telemt_desync_frames_bucket_total{bucket="gt_10"} 1047
telemt_pool_swap_total 31
telemt_pool_force_close_total 843
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 10999
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 931
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10368
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10156
telemt_me_writer_teardown_success_total{mode="normal"} 11299
telemt_me_writer_teardown_noop_total 10999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22298
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.468798
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22298
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 251
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 582006
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 9795385696 (9.12 GB)
telemt_user_octets_to_client{user="hello"} 206863394000 (192.66 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 103098.3 (28h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7581836
telemt_connections_bad_total 614913
telemt_connections_current 1485
telemt_connections_me_current 1485
telemt_handshake_timeouts_total 247599
telemt_upstream_connect_attempt_total 37798
telemt_upstream_connect_success_total 37725
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 37732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1543
telemt_me_reconnect_success_total 779
telemt_me_reader_eof_total 790
telemt_me_idle_close_by_peer_total 790
telemt_me_route_drop_no_conn_total 4516009
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6162997
telemt_me_endpoint_quarantine_total 654
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 769
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 26154
telemt_desync_full_logged_total 8635
telemt_desync_suppressed_total 17519
telemt_desync_frames_bucket_total{bucket="1_2"} 5626
telemt_desync_frames_bucket_total{bucket="3_10"} 10199
telemt_desync_frames_bucket_total{bucket="gt_10"} 10329
telemt_pool_swap_total 111
telemt_pool_force_close_total 3731
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 589
telemt_me_draining_writers_reap_progress_total 34470
telemt_me_writer_removed_unexpected_total 760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2897
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31876
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3492
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30739
telemt_me_writer_teardown_success_total{mode="normal"} 34773
telemt_me_writer_teardown_noop_total 34514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69287
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.361906
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69287
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 589
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 696
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6155270
telemt_user_connections_current{user="hello"} 1485
telemt_user_octets_from_client{user="hello"} 105401204764 (98.16 GB)
telemt_user_octets_to_client{user="hello"} 2038846082844 (1.85 TB)
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 103099.6 (28h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6243421
telemt_connections_bad_total 582528
telemt_connections_current 1595
telemt_connections_me_current 1595
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 207417
telemt_upstream_connect_attempt_total 41874
telemt_upstream_connect_success_total 41490
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 41677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1895
telemt_me_reconnect_success_total 842
telemt_me_reader_eof_total 811
telemt_me_idle_close_by_peer_total 811
telemt_me_route_drop_no_conn_total 2220024
telemt_me_route_drop_channel_closed_total 256
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4678718
telemt_me_endpoint_quarantine_total 637
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 791
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22315
telemt_desync_full_logged_total 7575
telemt_desync_suppressed_total 14740
telemt_desync_frames_bucket_total{bucket="1_2"} 5377
telemt_desync_frames_bucket_total{bucket="3_10"} 8656
telemt_desync_frames_bucket_total{bucket="gt_10"} 8282
telemt_pool_swap_total 112
telemt_pool_force_close_total 3367
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 33073
telemt_me_writer_removed_unexpected_total 797
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2816
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30990
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3154
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29706
telemt_me_writer_teardown_success_total{mode="normal"} 33806
telemt_me_writer_teardown_noop_total 33079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.200074
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 734
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4610376
telemt_user_connections_current{user="hello"} 1595
telemt_user_octets_from_client{user="hello"} 139247049909 (129.68 GB)
telemt_user_octets_to_client{user="hello"} 2165151250835 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 779
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 103064.0 (28h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6142334
telemt_connections_bad_total 544264
telemt_connections_current 1355
telemt_connections_me_current 1355
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 196731
telemt_upstream_connect_attempt_total 48171
telemt_upstream_connect_success_total 47837
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1935
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 805
telemt_me_idle_close_by_peer_total 805
telemt_me_route_drop_no_conn_total 2121568
telemt_me_route_drop_channel_closed_total 113
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4577030
telemt_me_endpoint_quarantine_total 714
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 772
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
telemt_me_writers_active_current 42
telemt_desync_total 22126
telemt_desync_full_logged_total 7404
telemt_desync_suppressed_total 14722
telemt_desync_frames_bucket_total{bucket="1_2"} 5404
telemt_desync_frames_bucket_total{bucket="3_10"} 8475
telemt_desync_frames_bucket_total{bucket="gt_10"} 8247
telemt_pool_swap_total 111
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 34452
telemt_me_writer_removed_unexpected_total 780
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2868
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32375
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3031
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31206
telemt_me_writer_teardown_success_total{mode="normal"} 35243
telemt_me_writer_teardown_noop_total 34463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69706
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.702511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69706
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 747
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4577703
telemt_user_connections_current{user="hello"} 1355
telemt_user_octets_from_client{user="hello"} 132687115479 (123.57 GB)
telemt_user_octets_to_client{user="hello"} 2090788986991 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 677
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 103103.0 (28h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20182276
telemt_connections_bad_total 1543039
telemt_connections_current 1962
telemt_connections_me_current 1962
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 590709
telemt_upstream_connect_attempt_total 191015
telemt_upstream_connect_success_total 173314
telemt_upstream_connect_fail_total 16052
telemt_upstream_connect_attempts_per_request{bucket="1"} 189366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8890
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16052
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64561
telemt_me_reconnect_success_total 2210
telemt_me_reader_eof_total 1392
telemt_me_idle_close_by_peer_total 1391
telemt_me_route_drop_no_conn_total 39478075
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16375167
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 798
telemt_me_single_endpoint_outage_enter_total 125
telemt_me_single_endpoint_outage_exit_total 125
telemt_me_single_endpoint_outage_reconnect_attempt_total 261
telemt_me_single_endpoint_outage_reconnect_success_total 64
telemt_me_single_endpoint_quarantine_bypass_total 261
telemt_me_single_endpoint_shadow_rotate_total 803
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 31694
telemt_desync_full_logged_total 9468
telemt_desync_suppressed_total 22226
telemt_desync_frames_bucket_total{bucket="1_2"} 6878
telemt_desync_frames_bucket_total{bucket="3_10"} 14069
telemt_desync_frames_bucket_total{bucket="gt_10"} 10747
telemt_pool_swap_total 106
telemt_pool_force_close_total 3491
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 774
telemt_me_draining_writers_reap_progress_total 32139
telemt_me_writer_removed_unexpected_total 2051
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4338
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29588
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2969
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28648
telemt_me_writer_teardown_success_total{mode="normal"} 33926
telemt_me_writer_teardown_noop_total 32165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66091
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 213.419443
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66091
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 774
telemt_me_refill_failed_total 3797
telemt_me_writer_restored_same_endpoint_total 1530
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 16502743
telemt_user_connections_current{user="hello"} 1962
telemt_user_octets_from_client{user="hello"} 201246079256 (187.43 GB)
telemt_user_octets_to_client{user="hello"} 1159081267198 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 976
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 103070.5 (28h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5915906
telemt_connections_bad_total 556148
telemt_connections_current 1468
telemt_connections_me_current 1468
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 123118
telemt_upstream_connect_attempt_total 56441
telemt_upstream_connect_success_total 55780
telemt_upstream_connect_fail_total 567
telemt_upstream_connect_attempts_per_request{bucket="1"} 56347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 567
telemt_me_reconnect_attempts_total 69508
telemt_me_reconnect_success_total 1742
telemt_me_reader_eof_total 1514
telemt_me_idle_close_by_peer_total 1513
telemt_me_route_drop_no_conn_total 2372671
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4615036
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 778
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
telemt_me_writers_active_current 42
telemt_desync_total 23187
telemt_desync_full_logged_total 8135
telemt_desync_suppressed_total 15052
telemt_desync_frames_bucket_total{bucket="1_2"} 4402
telemt_desync_frames_bucket_total{bucket="3_10"} 8972
telemt_desync_frames_bucket_total{bucket="gt_10"} 9813
telemt_pool_swap_total 106
telemt_pool_force_close_total 3089
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 35913
telemt_me_writer_removed_unexpected_total 1558
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3766
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33730
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2688
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32824
telemt_me_writer_teardown_success_total{mode="normal"} 37496
telemt_me_writer_teardown_noop_total 35914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73410
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.082208
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73410
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 4200
telemt_me_writer_restored_same_endpoint_total 1460
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 4608045
telemt_user_connections_current{user="hello"} 1468
telemt_user_octets_from_client{user="hello"} 123052970392 (114.60 GB)
telemt_user_octets_to_client{user="hello"} 1883804525022 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 738
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 39906.5 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3805365
telemt_connections_bad_total 138322
telemt_connections_current 1107
telemt_connections_me_current 1107
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1568507
telemt_upstream_connect_attempt_total 24770
telemt_upstream_connect_success_total 24606
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 24763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_reconnect_attempts_total 45761
telemt_me_reconnect_success_total 925
telemt_me_reader_eof_total 602
telemt_me_idle_close_by_peer_total 602
telemt_me_route_drop_no_conn_total 1008288
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1851177
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 305
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10153
telemt_desync_full_logged_total 3499
telemt_desync_suppressed_total 6654
telemt_desync_frames_bucket_total{bucket="1_2"} 1810
telemt_desync_frames_bucket_total{bucket="3_10"} 3881
telemt_desync_frames_bucket_total{bucket="gt_10"} 4462
telemt_pool_swap_total 43
telemt_pool_force_close_total 1372
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 14047
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1404
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13345
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1166
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12675
telemt_me_writer_teardown_success_total{mode="normal"} 14749
telemt_me_writer_teardown_noop_total 14049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28798
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.311295
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28798
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 2605
telemt_me_writer_restored_same_endpoint_total 827
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1854876
telemt_user_connections_current{user="hello"} 1107
telemt_user_octets_from_client{user="hello"} 53315329652 (49.65 GB)
telemt_user_octets_to_client{user="hello"} 793846520150 (739.33 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 20877.2 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176123
telemt_connections_bad_total 1494
telemt_connections_current 303
telemt_connections_me_current 303
telemt_handshake_timeouts_total 4862
telemt_upstream_connect_attempt_total 9932
telemt_upstream_connect_success_total 9908
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 9930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 220
telemt_me_reconnect_success_total 134
telemt_me_reader_eof_total 136
telemt_me_idle_close_by_peer_total 136
telemt_me_route_drop_no_conn_total 48840
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154734
telemt_me_endpoint_quarantine_total 210
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 996
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 23
telemt_pool_force_close_total 495
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 8914
telemt_me_writer_removed_unexpected_total 132
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 600
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8450
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 493
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8419
telemt_me_writer_teardown_success_total{mode="normal"} 9050
telemt_me_writer_teardown_noop_total 8914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17964
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.872200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17964
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 123
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 154445
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 2870571508 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 91125048744 (84.87 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 103074.8 (28h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7159632
telemt_connections_bad_total 728300
telemt_connections_current 1684
telemt_connections_me_current 1684
telemt_handshake_timeouts_total 204312
telemt_upstream_connect_attempt_total 39919
telemt_upstream_connect_success_total 39766
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 39882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20006
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_reconnect_attempts_total 1532
telemt_me_reconnect_success_total 816
telemt_me_reader_eof_total 798
telemt_me_idle_close_by_peer_total 798
telemt_me_route_drop_no_conn_total 2110205
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5389215
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 793
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20871
telemt_desync_full_logged_total 6957
telemt_desync_suppressed_total 13914
telemt_desync_frames_bucket_total{bucket="1_2"} 5100
telemt_desync_frames_bucket_total{bucket="3_10"} 7556
telemt_desync_frames_bucket_total{bucket="gt_10"} 8215
telemt_pool_swap_total 114
telemt_pool_force_close_total 3087
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 35960
telemt_me_writer_removed_unexpected_total 769
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2874
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32873
telemt_me_writer_teardown_success_total{mode="normal"} 36748
telemt_me_writer_teardown_noop_total 35962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72710
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.595686
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72710
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 726
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5364309
telemt_user_connections_current{user="hello"} 1684
telemt_user_octets_from_client{user="hello"} 108371550500 (100.93 GB)
telemt_user_octets_to_client{user="hello"} 2510803595984 (2.28 TB)
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 103071.5 (28h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6173086
telemt_connections_bad_total 609034
telemt_connections_current 1384
telemt_connections_me_current 1384
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 169848
telemt_upstream_connect_attempt_total 55760
telemt_upstream_connect_success_total 55342
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 55701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21690
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_reconnect_attempts_total 5441
telemt_me_reconnect_success_total 1130
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 2164368
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4758721
telemt_me_endpoint_quarantine_total 824
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 788
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 19691
telemt_desync_full_logged_total 6591
telemt_desync_suppressed_total 13100
telemt_desync_frames_bucket_total{bucket="1_2"} 4968
telemt_desync_frames_bucket_total{bucket="3_10"} 7166
telemt_desync_frames_bucket_total{bucket="gt_10"} 7557
telemt_pool_swap_total 112
telemt_pool_force_close_total 3044
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 34565
telemt_me_writer_removed_unexpected_total 1024
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3377
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32260
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2821
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31521
telemt_me_writer_teardown_success_total{mode="normal"} 35637
telemt_me_writer_teardown_noop_total 34569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70206
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.979061
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70206
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_restored_fallback_total 57
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4761867
telemt_user_connections_current{user="hello"} 1384
telemt_user_octets_from_client{user="hello"} 89674622829 (83.52 GB)
telemt_user_octets_to_client{user="hello"} 2038776595172 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 119
```