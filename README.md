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

# Server Metrics 2026-03-22 01:39:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 16398.4 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237742
telemt_connections_bad_total 16892
telemt_connections_current 616
telemt_connections_me_current 616
telemt_handshake_timeouts_total 13734
telemt_upstream_connect_attempt_total 6839
telemt_upstream_connect_success_total 6838
telemt_upstream_connect_attempts_per_request{bucket="1"} 6838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 234
telemt_me_reconnect_success_total 110
telemt_me_reader_eof_total 108
telemt_me_idle_close_by_peer_total 108
telemt_me_route_drop_no_conn_total 44486
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193914
telemt_me_endpoint_quarantine_total 133
telemt_me_single_endpoint_shadow_rotate_total 142
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
telemt_me_writers_active_current 45
telemt_desync_total 1691
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 614
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 18
telemt_pool_force_close_total 468
telemt_me_writer_close_signal_drop_total 33
telemt_me_draining_writers_reap_progress_total 6142
telemt_me_writer_removed_unexpected_total 109
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 437
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5803
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 463
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5674
telemt_me_writer_teardown_success_total{mode="normal"} 6240
telemt_me_writer_teardown_noop_total 6143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12383
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.145420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12383
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 33
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 100
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 193603
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 2094149812 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 66472567792 (61.91 GB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 29764.4 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743395
telemt_connections_bad_total 42875
telemt_connections_current 1013
telemt_connections_me_current 1013
telemt_handshake_timeouts_total 27699
telemt_upstream_connect_attempt_total 13559
telemt_upstream_connect_success_total 13338
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 13538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_reconnect_attempts_total 1140
telemt_me_reconnect_success_total 418
telemt_me_reader_eof_total 370
telemt_me_idle_close_by_peer_total 370
telemt_me_route_drop_no_conn_total 335519
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 594573
telemt_me_endpoint_quarantine_total 265
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 239
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
telemt_me_writers_active_current 92
telemt_me_writers_warm_current 12
telemt_desync_total 2598
telemt_desync_full_logged_total 1488
telemt_desync_suppressed_total 1110
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 982
telemt_desync_frames_bucket_total{bucket="gt_10"} 1062
telemt_pool_swap_total 31
telemt_pool_force_close_total 843
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 11938
telemt_me_writer_removed_unexpected_total 352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1013
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11282
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11095
telemt_me_writer_teardown_success_total{mode="normal"} 12295
telemt_me_writer_teardown_noop_total 11938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24233
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.483855
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24233
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 308
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 593706
telemt_user_connections_current{user="hello"} 1013
telemt_user_octets_from_client{user="hello"} 9883510592 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 213268938088 (198.62 GB)
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 104625.0 (29h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7626033
telemt_connections_bad_total 618896
telemt_connections_current 1041
telemt_connections_me_current 1041
telemt_handshake_timeouts_total 249576
telemt_upstream_connect_attempt_total 38518
telemt_upstream_connect_success_total 38445
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 38452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1550
telemt_me_reconnect_success_total 786
telemt_me_reader_eof_total 797
telemt_me_idle_close_by_peer_total 797
telemt_me_route_drop_no_conn_total 4521733
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6190349
telemt_me_endpoint_quarantine_total 675
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 781
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
telemt_me_writers_active_current 43
telemt_desync_total 26215
telemt_desync_full_logged_total 8662
telemt_desync_suppressed_total 17553
telemt_desync_frames_bucket_total{bucket="1_2"} 5641
telemt_desync_frames_bucket_total{bucket="3_10"} 10225
telemt_desync_frames_bucket_total{bucket="gt_10"} 10349
telemt_pool_swap_total 113
telemt_pool_force_close_total 3784
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 35150
telemt_me_writer_removed_unexpected_total 766
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2947
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32513
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3545
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31366
telemt_me_writer_teardown_success_total{mode="normal"} 35460
telemt_me_writer_teardown_noop_total 35194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.418833
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 702
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6182588
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 105577806524 (98.33 GB)
telemt_user_octets_to_client{user="hello"} 2049276574304 (1.86 TB)
telemt_user_unique_ips_current{user="hello"} 542
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 104626.2 (29h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6282960
telemt_connections_bad_total 583909
telemt_connections_current 1311
telemt_connections_me_current 1311
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 208580
telemt_upstream_connect_attempt_total 42554
telemt_upstream_connect_success_total 42169
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 42357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1904
telemt_me_reconnect_success_total 851
telemt_me_reader_eof_total 821
telemt_me_idle_close_by_peer_total 821
telemt_me_route_drop_no_conn_total 2244381
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4712296
telemt_me_endpoint_quarantine_total 651
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 803
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
telemt_me_writers_active_current 45
telemt_desync_total 22369
telemt_desync_full_logged_total 7603
telemt_desync_suppressed_total 14766
telemt_desync_frames_bucket_total{bucket="1_2"} 5385
telemt_desync_frames_bucket_total{bucket="3_10"} 8677
telemt_desync_frames_bucket_total{bucket="gt_10"} 8307
telemt_pool_swap_total 114
telemt_pool_force_close_total 3419
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 357
telemt_me_draining_writers_reap_progress_total 33693
telemt_me_writer_removed_unexpected_total 806
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2856
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31580
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30274
telemt_me_writer_teardown_success_total{mode="normal"} 34436
telemt_me_writer_teardown_noop_total 33699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68135
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.226688
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68135
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 357
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 743
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4634556
telemt_user_connections_current{user="hello"} 1311
telemt_user_octets_from_client{user="hello"} 139498329877 (129.92 GB)
telemt_user_octets_to_client{user="hello"} 2180262663303 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 310
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 104591.5 (29h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6178006
telemt_connections_bad_total 545152
telemt_connections_current 1222
telemt_connections_me_current 1222
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 197929
telemt_upstream_connect_attempt_total 48820
telemt_upstream_connect_success_total 48472
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 48608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1060
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1945
telemt_me_reconnect_success_total 872
telemt_me_reader_eof_total 816
telemt_me_idle_close_by_peer_total 816
telemt_me_route_drop_no_conn_total 2137166
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4606714
telemt_me_endpoint_quarantine_total 730
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 782
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
telemt_me_writers_active_current 43
telemt_desync_total 22202
telemt_desync_full_logged_total 7440
telemt_desync_suppressed_total 14762
telemt_desync_frames_bucket_total{bucket="1_2"} 5425
telemt_desync_frames_bucket_total{bucket="3_10"} 8504
telemt_desync_frames_bucket_total{bucket="gt_10"} 8273
telemt_pool_swap_total 113
telemt_pool_force_close_total 3291
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 35021
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2905
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32918
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3076
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31730
telemt_me_writer_teardown_success_total{mode="normal"} 35823
telemt_me_writer_teardown_noop_total 35032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.748200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 756
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4602432
telemt_user_connections_current{user="hello"} 1222
telemt_user_octets_from_client{user="hello"} 132914086355 (123.79 GB)
telemt_user_octets_to_client{user="hello"} 2101430299775 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 382
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 104629.1 (29h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20248032
telemt_connections_bad_total 1565474
telemt_connections_current 1764
telemt_connections_me_current 1764
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 594612
telemt_upstream_connect_attempt_total 193916
telemt_upstream_connect_success_total 175998
telemt_upstream_connect_fail_total 16220
telemt_upstream_connect_attempts_per_request{bucket="1"} 192218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8910
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16220
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64770
telemt_me_reconnect_success_total 2274
telemt_me_reader_eof_total 1411
telemt_me_idle_close_by_peer_total 1410
telemt_me_route_drop_no_conn_total 39487063
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16410901
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 816
telemt_me_single_endpoint_outage_enter_total 133
telemt_me_single_endpoint_outage_exit_total 133
telemt_me_single_endpoint_outage_reconnect_attempt_total 283
telemt_me_single_endpoint_outage_reconnect_success_total 68
telemt_me_single_endpoint_quarantine_bypass_total 283
telemt_me_single_endpoint_shadow_rotate_total 818
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 31802
telemt_desync_full_logged_total 9502
telemt_desync_suppressed_total 22300
telemt_desync_frames_bucket_total{bucket="1_2"} 6894
telemt_desync_frames_bucket_total{bucket="3_10"} 14107
telemt_desync_frames_bucket_total{bucket="gt_10"} 10801
telemt_pool_swap_total 108
telemt_pool_force_close_total 3548
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 788
telemt_me_draining_writers_reap_progress_total 32626
telemt_me_writer_removed_unexpected_total 2114
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4440
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30036
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29078
telemt_me_writer_teardown_success_total{mode="normal"} 34476
telemt_me_writer_teardown_noop_total 32652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67128
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 213.702872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67128
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 788
telemt_me_refill_failed_total 3799
telemt_me_writer_restored_same_endpoint_total 1557
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 16540489
telemt_user_connections_current{user="hello"} 1764
telemt_user_octets_from_client{user="hello"} 205847651994 (191.71 GB)
telemt_user_octets_to_client{user="hello"} 1168579879099 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 815
telemt_user_unique_ips_recent_window{user="hello"} 594
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 104596.5 (29h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5941805
telemt_connections_bad_total 557582
telemt_connections_current 1448
telemt_connections_me_current 1448
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 123959
telemt_upstream_connect_attempt_total 57192
telemt_upstream_connect_success_total 56522
telemt_upstream_connect_fail_total 573
telemt_upstream_connect_attempts_per_request{bucket="1"} 57095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 573
telemt_me_reconnect_attempts_total 69582
telemt_me_reconnect_success_total 1755
telemt_me_reader_eof_total 1529
telemt_me_idle_close_by_peer_total 1528
telemt_me_route_drop_no_conn_total 2377189
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4636078
telemt_me_endpoint_quarantine_total 710
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 787
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
telemt_me_writers_active_current 42
telemt_desync_total 23228
telemt_desync_full_logged_total 8161
telemt_desync_suppressed_total 15067
telemt_desync_frames_bucket_total{bucket="1_2"} 4412
telemt_desync_frames_bucket_total{bucket="3_10"} 8991
telemt_desync_frames_bucket_total{bucket="gt_10"} 9825
telemt_pool_swap_total 108
telemt_pool_force_close_total 3112
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 36558
telemt_me_writer_removed_unexpected_total 1571
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3799
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34357
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2711
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33446
telemt_me_writer_teardown_success_total{mode="normal"} 38156
telemt_me_writer_teardown_noop_total 36559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74715
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.092095
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74715
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 4204
telemt_me_writer_restored_same_endpoint_total 1469
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 4629074
telemt_user_connections_current{user="hello"} 1448
telemt_user_octets_from_client{user="hello"} 123233500740 (114.77 GB)
telemt_user_octets_to_client{user="hello"} 1892782140638 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 41432.4 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3832814
telemt_connections_bad_total 139152
telemt_connections_current 1111
telemt_connections_me_current 1111
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1573761
telemt_upstream_connect_attempt_total 25527
telemt_upstream_connect_success_total 25360
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 25520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_reconnect_attempts_total 45772
telemt_me_reconnect_success_total 936
telemt_me_reader_eof_total 613
telemt_me_idle_close_by_peer_total 613
telemt_me_route_drop_no_conn_total 1011930
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1870870
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_warm_current 5
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10221
telemt_desync_full_logged_total 3533
telemt_desync_suppressed_total 6688
telemt_desync_frames_bucket_total{bucket="1_2"} 1828
telemt_desync_frames_bucket_total{bucket="3_10"} 3909
telemt_desync_frames_bucket_total{bucket="gt_10"} 4484
telemt_pool_swap_total 44
telemt_pool_force_close_total 1390
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 14731
telemt_me_writer_removed_unexpected_total 691
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1432
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14012
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13341
telemt_me_writer_teardown_success_total{mode="normal"} 15444
telemt_me_writer_teardown_noop_total 14733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.316006
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 2605
telemt_me_writer_restored_same_endpoint_total 837
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1874560
telemt_user_connections_current{user="hello"} 1111
telemt_user_octets_from_client{user="hello"} 53488006072 (49.81 GB)
telemt_user_octets_to_client{user="hello"} 799979213950 (745.04 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 617
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 22403.3 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182153
telemt_connections_bad_total 1616
telemt_connections_current 259
telemt_connections_me_current 259
telemt_handshake_timeouts_total 5016
telemt_upstream_connect_attempt_total 10673
telemt_upstream_connect_success_total 10649
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 10671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 227
telemt_me_reconnect_success_total 141
telemt_me_reader_eof_total 144
telemt_me_idle_close_by_peer_total 144
telemt_me_route_drop_no_conn_total 49977
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160225
telemt_me_endpoint_quarantine_total 218
telemt_me_single_endpoint_shadow_rotate_total 196
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
telemt_desync_total 1006
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 753
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 24
telemt_pool_force_close_total 537
telemt_me_writer_close_signal_drop_total 21
telemt_me_draining_writers_reap_progress_total 9616
telemt_me_writer_removed_unexpected_total 139
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 636
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9124
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9079
telemt_me_writer_teardown_success_total{mode="normal"} 9760
telemt_me_writer_teardown_noop_total 9616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19376
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.916492
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19376
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 21
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 159931
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 2919427056 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 92632848244 (86.27 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 104600.9 (29h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7208151
telemt_connections_bad_total 734877
telemt_connections_current 1417
telemt_connections_me_current 1417
telemt_handshake_timeouts_total 205407
telemt_upstream_connect_attempt_total 40683
telemt_upstream_connect_success_total 40529
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 40646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_reconnect_attempts_total 1541
telemt_me_reconnect_success_total 824
telemt_me_reader_eof_total 806
telemt_me_idle_close_by_peer_total 806
telemt_me_route_drop_no_conn_total 2114790
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5416149
telemt_me_endpoint_quarantine_total 727
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 804
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
telemt_me_writers_active_current 44
telemt_desync_total 21280
telemt_desync_full_logged_total 6985
telemt_desync_suppressed_total 14295
telemt_desync_frames_bucket_total{bucket="1_2"} 5333
telemt_desync_frames_bucket_total{bucket="3_10"} 7702
telemt_desync_frames_bucket_total{bucket="gt_10"} 8245
telemt_pool_swap_total 116
telemt_pool_force_close_total 3128
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 36669
telemt_me_writer_removed_unexpected_total 777
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2914
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34551
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33541
telemt_me_writer_teardown_success_total{mode="normal"} 37465
telemt_me_writer_teardown_noop_total 36671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.612218
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 734
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5391196
telemt_user_connections_current{user="hello"} 1417
telemt_user_octets_from_client{user="hello"} 108574166816 (101.12 GB)
telemt_user_octets_to_client{user="hello"} 2517869729312 (2.29 TB)
telemt_user_unique_ips_current{user="hello"} 603
telemt_user_unique_ips_recent_window{user="hello"} 536
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 104597.6 (29h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6215306
telemt_connections_bad_total 612460
telemt_connections_current 1331
telemt_connections_me_current 1331
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 170644
telemt_upstream_connect_attempt_total 56481
telemt_upstream_connect_success_total 56059
telemt_upstream_connect_fail_total 363
telemt_upstream_connect_attempts_per_request{bucket="1"} 56422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 363
telemt_me_reconnect_attempts_total 5502
telemt_me_reconnect_success_total 1138
telemt_me_reader_eof_total 1020
telemt_me_idle_close_by_peer_total 1020
telemt_me_seq_mismatch_total 45
telemt_me_route_drop_no_conn_total 2168138
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4783967
telemt_me_endpoint_quarantine_total 834
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 800
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
telemt_me_writers_active_current 43
telemt_desync_total 19930
telemt_desync_full_logged_total 6621
telemt_desync_suppressed_total 13309
telemt_desync_frames_bucket_total{bucket="1_2"} 5084
telemt_desync_frames_bucket_total{bucket="3_10"} 7259
telemt_desync_frames_bucket_total{bucket="gt_10"} 7587
telemt_pool_swap_total 114
telemt_pool_force_close_total 3085
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 35246
telemt_me_writer_removed_unexpected_total 1032
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3426
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32900
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2862
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32161
telemt_me_writer_teardown_success_total{mode="normal"} 36326
telemt_me_writer_teardown_noop_total 35250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.990741
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4787085
telemt_user_connections_current{user="hello"} 1331
telemt_user_octets_from_client{user="hello"} 89969781517 (83.79 GB)
telemt_user_octets_to_client{user="hello"} 2048537741120 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 524
```