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

# Server Metrics 2026-03-21 07:29:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 39196.7 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 905560
telemt_connections_bad_total 47810
telemt_connections_current 1476
telemt_connections_me_current 1476
telemt_handshake_timeouts_total 42432
telemt_upstream_connect_attempt_total 15652
telemt_upstream_connect_success_total 15581
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 15629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 502
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 289757
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661571
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 277
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 322
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
telemt_me_writers_active_current 42
telemt_desync_total 2931
telemt_desync_full_logged_total 1048
telemt_desync_suppressed_total 1883
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 1150
telemt_desync_frames_bucket_total{bucket="gt_10"} 1177
telemt_pool_swap_total 43
telemt_pool_force_close_total 1192
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 14134
telemt_me_writer_removed_unexpected_total 245
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13287
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12942
telemt_me_writer_teardown_success_total{mode="normal"} 14334
telemt_me_writer_teardown_noop_total 14135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28469
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.925670
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28469
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 660794
telemt_user_connections_current{user="hello"} 1476
telemt_user_octets_from_client{user="hello"} 7962708004 (7.42 GB)
telemt_user_octets_to_client{user="hello"} 208325123996 (194.02 GB)
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 39198.2 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2231495
telemt_connections_bad_total 246396
telemt_connections_current 3927
telemt_connections_me_current 3927
telemt_handshake_timeouts_total 67595
telemt_upstream_connect_attempt_total 14613
telemt_upstream_connect_success_total 14546
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 14592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 862
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 301
telemt_me_idle_close_by_peer_total 300
telemt_me_route_drop_no_conn_total 474719
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1378590
telemt_me_endpoint_quarantine_total 253
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 313
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
telemt_me_writers_active_current 43
telemt_desync_total 5916
telemt_desync_full_logged_total 2072
telemt_desync_suppressed_total 3844
telemt_desync_frames_bucket_total{bucket="1_2"} 1207
telemt_desync_frames_bucket_total{bucket="3_10"} 2334
telemt_desync_frames_bucket_total{bucket="gt_10"} 2375
telemt_pool_swap_total 42
telemt_pool_force_close_total 1250
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 13111
telemt_me_writer_removed_unexpected_total 282
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1164
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12221
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1192
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11861
telemt_me_writer_teardown_success_total{mode="normal"} 13385
telemt_me_writer_teardown_noop_total 13111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26496
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.068768
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26496
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1375467
telemt_user_connections_current{user="hello"} 3927
telemt_user_octets_from_client{user="hello"} 18919791320 (17.62 GB)
telemt_user_octets_to_client{user="hello"} 563465556276 (524.77 GB)
telemt_user_unique_ips_current{user="hello"} 1497
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 39194.6 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1513036
telemt_connections_bad_total 165082
telemt_connections_current 3312
telemt_connections_me_current 3312
telemt_handshake_timeouts_total 67396
telemt_upstream_connect_attempt_total 15730
telemt_upstream_connect_success_total 15720
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 487
telemt_me_reconnect_success_total 256
telemt_me_reader_eof_total 265
telemt_me_idle_close_by_peer_total 265
telemt_me_route_drop_no_conn_total 397998
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1183718
telemt_me_endpoint_quarantine_total 279
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 4834
telemt_desync_full_logged_total 1728
telemt_desync_suppressed_total 3106
telemt_desync_frames_bucket_total{bucket="1_2"} 1057
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 1932
telemt_pool_swap_total 43
telemt_pool_force_close_total 1214
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 14340
telemt_me_writer_removed_unexpected_total 247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1115
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13386
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1196
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13126
telemt_me_writer_teardown_success_total{mode="normal"} 14501
telemt_me_writer_teardown_noop_total 14343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28844
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.057185
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28844
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 219
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1181329
telemt_user_connections_current{user="hello"} 3312
telemt_user_octets_from_client{user="hello"} 16199856764 (15.09 GB)
telemt_user_octets_to_client{user="hello"} 521469052128 (485.66 GB)
telemt_user_unique_ips_current{user="hello"} 1260
telemt_user_unique_ips_recent_window{user="hello"} 437
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 39196.0 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1310050
telemt_connections_bad_total 159898
telemt_connections_current 2759
telemt_connections_me_current 2759
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 60265
telemt_upstream_connect_attempt_total 20568
telemt_upstream_connect_success_total 20345
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 20464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 732
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 298
telemt_me_idle_close_by_peer_total 298
telemt_me_route_drop_no_conn_total 372663
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 909651
telemt_me_endpoint_quarantine_total 285
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 317
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
telemt_me_writers_active_current 44
telemt_desync_total 4168
telemt_desync_full_logged_total 1494
telemt_desync_suppressed_total 2674
telemt_desync_frames_bucket_total{bucket="1_2"} 954
telemt_desync_frames_bucket_total{bucket="3_10"} 1755
telemt_desync_frames_bucket_total{bucket="gt_10"} 1459
telemt_pool_swap_total 43
telemt_pool_force_close_total 1102
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 14194
telemt_me_writer_removed_unexpected_total 290
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1083
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13415
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1076
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13092
telemt_me_writer_teardown_success_total{mode="normal"} 14498
telemt_me_writer_teardown_noop_total 14195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.670710
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 263
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 912527
telemt_user_connections_current{user="hello"} 2759
telemt_user_octets_from_client{user="hello"} 16034194345 (14.93 GB)
telemt_user_octets_to_client{user="hello"} 425238729799 (396.03 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1054
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 39160.1 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1264967
telemt_connections_bad_total 149776
telemt_connections_current 2744
telemt_connections_me_current 2744
telemt_handshake_timeouts_total 44863
telemt_upstream_connect_attempt_total 16492
telemt_upstream_connect_success_total 16483
telemt_upstream_connect_attempts_per_request{bucket="1"} 16483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9129
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 323
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 242
telemt_me_idle_close_by_peer_total 242
telemt_me_route_drop_no_conn_total 269267
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901035
telemt_me_endpoint_quarantine_total 317
telemt_me_single_endpoint_shadow_rotate_total 311
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 4349
telemt_desync_full_logged_total 1571
telemt_desync_suppressed_total 2778
telemt_desync_frames_bucket_total{bucket="1_2"} 1079
telemt_desync_frames_bucket_total{bucket="3_10"} 1687
telemt_desync_frames_bucket_total{bucket="gt_10"} 1583
telemt_pool_swap_total 43
telemt_pool_force_close_total 1077
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 74
telemt_me_draining_writers_reap_progress_total 14958
telemt_me_writer_removed_unexpected_total 222
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1000
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14201
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13881
telemt_me_writer_teardown_success_total{mode="normal"} 15201
telemt_me_writer_teardown_noop_total 14961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30162
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.125312
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30162
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 74
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 899408
telemt_user_connections_current{user="hello"} 2744
telemt_user_octets_from_client{user="hello"} 23717647684 (22.09 GB)
telemt_user_octets_to_client{user="hello"} 468568726572 (436.39 GB)
telemt_user_unique_ips_current{user="hello"} 1000
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 39199.2 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2950943
telemt_connections_bad_total 188274
telemt_connections_current 4749
telemt_connections_me_current 4749
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 170299
telemt_upstream_connect_attempt_total 41991
telemt_upstream_connect_success_total 40087
telemt_upstream_connect_fail_total 1352
telemt_upstream_connect_attempts_per_request{bucket="1"} 41439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1352
telemt_me_reconnect_attempts_total 1971
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 419
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 3187755
telemt_me_route_drop_channel_closed_total 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2383983
telemt_me_endpoint_quarantine_total 316
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 317
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
telemt_me_writers_active_current 45
telemt_desync_total 5688
telemt_desync_full_logged_total 2037
telemt_desync_suppressed_total 3651
telemt_desync_frames_bucket_total{bucket="1_2"} 1296
telemt_desync_frames_bucket_total{bucket="3_10"} 2397
telemt_desync_frames_bucket_total{bucket="gt_10"} 1995
telemt_pool_swap_total 42
telemt_pool_force_close_total 1184
telemt_me_writer_close_signal_drop_total 188
telemt_me_draining_writers_reap_progress_total 13283
telemt_me_writer_removed_unexpected_total 635
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1552
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12335
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1104
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12099
telemt_me_writer_teardown_success_total{mode="normal"} 13887
telemt_me_writer_teardown_noop_total 13288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27175
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.458735
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27175
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 188
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 422
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 2406482
telemt_user_connections_current{user="hello"} 4749
telemt_user_octets_from_client{user="hello"} 35752306722 (33.30 GB)
telemt_user_octets_to_client{user="hello"} 483232379062 (450.05 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1652
telemt_user_unique_ips_recent_window{user="hello"} 755
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 39166.9 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1346629
telemt_connections_bad_total 194626
telemt_connections_current 2781
telemt_connections_me_current 2781
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 27820
telemt_upstream_connect_attempt_total 18312
telemt_upstream_connect_success_total 18149
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 18296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 1631
telemt_me_reconnect_success_total 505
telemt_me_reader_eof_total 520
telemt_me_idle_close_by_peer_total 520
telemt_me_route_drop_no_conn_total 334710
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 975245
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 315
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 4087
telemt_desync_full_logged_total 1550
telemt_desync_suppressed_total 2537
telemt_desync_frames_bucket_total{bucket="1_2"} 785
telemt_desync_frames_bucket_total{bucket="3_10"} 1654
telemt_desync_frames_bucket_total{bucket="gt_10"} 1648
telemt_pool_swap_total 41
telemt_pool_force_close_total 1029
telemt_me_writer_close_signal_drop_total 63
telemt_me_draining_writers_reap_progress_total 15081
telemt_me_writer_removed_unexpected_total 499
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1282
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14319
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 971
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14052
telemt_me_writer_teardown_success_total{mode="normal"} 15601
telemt_me_writer_teardown_noop_total 15081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30682
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.096375
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30682
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 63
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 426
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 972753
telemt_user_connections_current{user="hello"} 2781
telemt_user_octets_from_client{user="hello"} 16243179108 (15.13 GB)
telemt_user_octets_to_client{user="hello"} 474514175418 (441.93 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1087
telemt_user_unique_ips_recent_window{user="hello"} 374
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 39161.4 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1735169
telemt_connections_bad_total 115207
telemt_connections_current 2492
telemt_connections_me_current 2492
telemt_handshake_timeouts_total 633805
telemt_upstream_connect_attempt_total 17117
telemt_upstream_connect_success_total 17089
telemt_upstream_connect_attempts_per_request{bucket="1"} 17089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 360
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 300991
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 865611
telemt_me_endpoint_quarantine_total 332
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
telemt_me_writers_active_current 43
telemt_desync_total 4108
telemt_desync_full_logged_total 1460
telemt_desync_suppressed_total 2648
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 1681
telemt_desync_frames_bucket_total{bucket="gt_10"} 1712
telemt_pool_swap_total 43
telemt_pool_force_close_total 1005
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 15350
telemt_me_writer_removed_unexpected_total 244
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14692
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14345
telemt_me_writer_teardown_success_total{mode="normal"} 15612
telemt_me_writer_teardown_noop_total 15350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30962
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.551278
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30962
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 226
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 862518
telemt_user_connections_current{user="hello"} 2492
telemt_user_octets_from_client{user="hello"} 14581547128 (13.58 GB)
telemt_user_octets_to_client{user="hello"} 443249775016 (412.81 GB)
telemt_user_unique_ips_current{user="hello"} 1021
telemt_user_unique_ips_recent_window{user="hello"} 350
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 37152.8 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343162
telemt_connections_bad_total 12064
telemt_connections_current 551
telemt_connections_me_current 551
telemt_handshake_timeouts_total 97886
telemt_upstream_connect_attempt_total 18732
telemt_upstream_connect_success_total 18731
telemt_upstream_connect_attempts_per_request{bucket="1"} 18731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 706
telemt_me_reconnect_success_total 291
telemt_me_reader_eof_total 294
telemt_me_idle_close_by_peer_total 294
telemt_me_route_drop_no_conn_total 80310
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210419
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 324
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
telemt_desync_total 1283
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 695
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 534
telemt_desync_frames_bucket_total{bucket="gt_10"} 504
telemt_pool_swap_total 41
telemt_pool_force_close_total 850
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 49
telemt_me_draining_writers_reap_progress_total 16718
telemt_me_writer_removed_unexpected_total 277
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1173
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15824
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 850
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15868
telemt_me_writer_teardown_success_total{mode="normal"} 16997
telemt_me_writer_teardown_noop_total 16718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33715
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.277328
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33715
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 49
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 210619
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 2653836695 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 90516596385 (84.30 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 39171.1 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1370780
telemt_connections_bad_total 108817
telemt_connections_current 3040
telemt_connections_me_current 3040
telemt_handshake_timeouts_total 35865
telemt_upstream_connect_attempt_total 17582
telemt_upstream_connect_success_total 17502
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 17553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 592
telemt_me_reconnect_success_total 347
telemt_me_reader_eof_total 330
telemt_me_idle_close_by_peer_total 330
telemt_me_route_drop_no_conn_total 305258
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1072436
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 316
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
telemt_me_writers_active_current 45
telemt_desync_total 4252
telemt_desync_full_logged_total 1433
telemt_desync_suppressed_total 2819
telemt_desync_frames_bucket_total{bucket="1_2"} 1095
telemt_desync_frames_bucket_total{bucket="3_10"} 1586
telemt_desync_frames_bucket_total{bucket="gt_10"} 1571
telemt_pool_swap_total 43
telemt_pool_force_close_total 1018
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 15879
telemt_me_writer_removed_unexpected_total 331
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1119
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15098
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1013
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14861
telemt_me_writer_teardown_success_total{mode="normal"} 16217
telemt_me_writer_teardown_noop_total 15879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32096
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.639749
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32096
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 316
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1067855
telemt_user_connections_current{user="hello"} 3040
telemt_user_octets_from_client{user="hello"} 17381309624 (16.19 GB)
telemt_user_octets_to_client{user="hello"} 489623497008 (456.00 GB)
telemt_user_unique_ips_current{user="hello"} 1155
telemt_user_unique_ips_recent_window{user="hello"} 391
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 39167.8 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1304468
telemt_connections_bad_total 93808
telemt_connections_current 3109
telemt_connections_me_current 3109
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 33488
telemt_upstream_connect_attempt_total 26094
telemt_upstream_connect_success_total 25906
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 26054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_reconnect_attempts_total 2589
telemt_me_reconnect_success_total 467
telemt_me_reader_eof_total 410
telemt_me_idle_close_by_peer_total 410
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 309614
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1040265
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 312
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 4169
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 2864
telemt_desync_frames_bucket_total{bucket="1_2"} 1201
telemt_desync_frames_bucket_total{bucket="3_10"} 1527
telemt_desync_frames_bucket_total{bucket="gt_10"} 1441
telemt_pool_swap_total 43
telemt_pool_force_close_total 985
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 15051
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14172
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 965
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14066
telemt_me_writer_teardown_success_total{mode="normal"} 15495
telemt_me_writer_teardown_noop_total 15051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30546
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.583816
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30546
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 347
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1044891
telemt_user_connections_current{user="hello"} 3109
telemt_user_octets_from_client{user="hello"} 13641240595 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 461785778807 (430.07 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1151
telemt_user_unique_ips_recent_window{user="hello"} 430
```