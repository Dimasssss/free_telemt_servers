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

# Server Metrics 2026-03-21 07:13:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 38283.0 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 860040
telemt_connections_bad_total 46296
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_handshake_timeouts_total 41201
telemt_upstream_connect_attempt_total 15377
telemt_upstream_connect_success_total 15307
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 15354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 485
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 258
telemt_me_idle_close_by_peer_total 258
telemt_me_route_drop_no_conn_total 279736
telemt_me_route_drop_channel_closed_total 99
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633607
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 271
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 315
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
telemt_desync_total 2770
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 1767
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 1086
telemt_desync_frames_bucket_total{bucket="gt_10"} 1106
telemt_pool_swap_total 42
telemt_pool_force_close_total 1156
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 13871
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13050
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12715
telemt_me_writer_teardown_success_total{mode="normal"} 14072
telemt_me_writer_teardown_noop_total 13872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27944
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.067988
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27944
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 222
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 632847
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 7563723872 (7.04 GB)
telemt_user_octets_to_client{user="hello"} 200130364256 (186.39 GB)
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 38284.2 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2140627
telemt_connections_bad_total 236549
telemt_connections_current 3915
telemt_connections_me_current 3915
telemt_handshake_timeouts_total 66113
telemt_upstream_connect_attempt_total 14325
telemt_upstream_connect_success_total 14258
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 14304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 288
telemt_me_reader_eof_total 297
telemt_me_idle_close_by_peer_total 296
telemt_me_route_drop_no_conn_total 444747
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1307974
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 307
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
telemt_desync_total 5666
telemt_desync_full_logged_total 1978
telemt_desync_suppressed_total 3688
telemt_desync_frames_bucket_total{bucket="1_2"} 1149
telemt_desync_frames_bucket_total{bucket="3_10"} 2227
telemt_desync_frames_bucket_total{bucket="gt_10"} 2290
telemt_pool_swap_total 41
telemt_pool_force_close_total 1221
telemt_me_writer_close_signal_drop_total 125
telemt_me_draining_writers_reap_progress_total 12849
telemt_me_writer_removed_unexpected_total 278
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1138
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11981
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1165
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11628
telemt_me_writer_teardown_success_total{mode="normal"} 13119
telemt_me_writer_teardown_noop_total 12849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.608586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 125
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 240
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1304888
telemt_user_connections_current{user="hello"} 3915
telemt_user_octets_from_client{user="hello"} 17954643764 (16.72 GB)
telemt_user_octets_to_client{user="hello"} 538110128876 (501.15 GB)
telemt_user_unique_ips_current{user="hello"} 1464
telemt_user_unique_ips_recent_window{user="hello"} 559
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 38280.7 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1443755
telemt_connections_bad_total 162778
telemt_connections_current 3463
telemt_connections_me_current 3463
telemt_handshake_timeouts_total 65238
telemt_upstream_connect_attempt_total 15459
telemt_upstream_connect_success_total 15449
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 482
telemt_me_reconnect_success_total 252
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 374161
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1126174
telemt_me_endpoint_quarantine_total 271
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 307
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
telemt_me_writers_active_current 45
telemt_desync_total 4527
telemt_desync_full_logged_total 1630
telemt_desync_suppressed_total 2897
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1749
telemt_desync_frames_bucket_total{bucket="gt_10"} 1773
telemt_pool_swap_total 42
telemt_pool_force_close_total 1182
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 14087
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1095
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13149
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1168
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12905
telemt_me_writer_teardown_success_total{mode="normal"} 14244
telemt_me_writer_teardown_noop_total 14090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28334
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.563376
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28334
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 215
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1123877
telemt_user_connections_current{user="hello"} 3463
telemt_user_octets_from_client{user="hello"} 15379159560 (14.32 GB)
telemt_user_octets_to_client{user="hello"} 496197301696 (462.12 GB)
telemt_user_unique_ips_current{user="hello"} 1298
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 38281.7 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1254732
telemt_connections_bad_total 157821
telemt_connections_current 2652
telemt_connections_me_current 2652
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 58772
telemt_upstream_connect_attempt_total 20279
telemt_upstream_connect_success_total 20063
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 375
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 716
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 292
telemt_me_idle_close_by_peer_total 292
telemt_me_route_drop_no_conn_total 353820
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 863102
telemt_me_endpoint_quarantine_total 279
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 311
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
telemt_desync_total 3992
telemt_desync_full_logged_total 1426
telemt_desync_suppressed_total 2566
telemt_desync_frames_bucket_total{bucket="1_2"} 904
telemt_desync_frames_bucket_total{bucket="3_10"} 1678
telemt_desync_frames_bucket_total{bucket="gt_10"} 1410
telemt_pool_swap_total 42
telemt_pool_force_close_total 1073
telemt_me_writer_close_signal_drop_total 57
telemt_me_draining_writers_reap_progress_total 13946
telemt_me_writer_removed_unexpected_total 284
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1063
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13181
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1050
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12873
telemt_me_writer_teardown_success_total{mode="normal"} 14244
telemt_me_writer_teardown_noop_total 13947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28191
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.474335
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28191
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 57
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 257
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 866072
telemt_user_connections_current{user="hello"} 2652
telemt_user_octets_from_client{user="hello"} 14895782245 (13.87 GB)
telemt_user_octets_to_client{user="hello"} 405702246815 (377.84 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1018
telemt_user_unique_ips_recent_window{user="hello"} 359
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 38245.7 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1199467
telemt_connections_bad_total 148097
telemt_connections_current 2846
telemt_connections_me_current 2846
telemt_handshake_timeouts_total 43384
telemt_upstream_connect_attempt_total 16170
telemt_upstream_connect_success_total 16161
telemt_upstream_connect_attempts_per_request{bucket="1"} 16161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 283
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 235
telemt_me_idle_close_by_peer_total 235
telemt_me_route_drop_no_conn_total 252304
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 853038
telemt_me_endpoint_quarantine_total 313
telemt_me_single_endpoint_shadow_rotate_total 305
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
telemt_me_writers_active_current 45
telemt_desync_total 4099
telemt_desync_full_logged_total 1496
telemt_desync_suppressed_total 2603
telemt_desync_frames_bucket_total{bucket="1_2"} 1014
telemt_desync_frames_bucket_total{bucket="3_10"} 1583
telemt_desync_frames_bucket_total{bucket="gt_10"} 1502
telemt_pool_swap_total 42
telemt_pool_force_close_total 1048
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 71
telemt_me_draining_writers_reap_progress_total 14669
telemt_me_writer_removed_unexpected_total 216
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 967
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13938
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1038
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13621
telemt_me_writer_teardown_success_total{mode="normal"} 14905
telemt_me_writer_teardown_noop_total 14670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29575
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.656274
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29575
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 71
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 851473
telemt_user_connections_current{user="hello"} 2846
telemt_user_octets_from_client{user="hello"} 21842398660 (20.34 GB)
telemt_user_octets_to_client{user="hello"} 443525852716 (413.07 GB)
telemt_user_unique_ips_current{user="hello"} 1048
telemt_user_unique_ips_recent_window{user="hello"} 385
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 38285.3 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2707841
telemt_connections_bad_total 180933
telemt_connections_current 4639
telemt_connections_me_current 4639
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 162966
telemt_upstream_connect_attempt_total 41677
telemt_upstream_connect_success_total 39785
telemt_upstream_connect_fail_total 1350
telemt_upstream_connect_attempts_per_request{bucket="1"} 41135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1350
telemt_me_reconnect_attempts_total 1950
telemt_me_reconnect_success_total 654
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 411
telemt_me_route_drop_no_conn_total 2703993
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2168819
telemt_me_endpoint_quarantine_total 310
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 312
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 5240
telemt_desync_full_logged_total 1901
telemt_desync_suppressed_total 3339
telemt_desync_frames_bucket_total{bucket="1_2"} 1194
telemt_desync_frames_bucket_total{bucket="3_10"} 2213
telemt_desync_frames_bucket_total{bucket="gt_10"} 1833
telemt_pool_swap_total 41
telemt_pool_force_close_total 1144
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 13005
telemt_me_writer_removed_unexpected_total 628
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1524
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12078
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1073
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11861
telemt_me_writer_teardown_success_total{mode="normal"} 13602
telemt_me_writer_teardown_noop_total 13009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26611
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.820489
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26611
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 412
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 2191414
telemt_user_connections_current{user="hello"} 4639
telemt_user_octets_from_client{user="hello"} 34719296838 (32.33 GB)
telemt_user_octets_to_client{user="hello"} 472457333922 (440.01 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1582
telemt_user_unique_ips_recent_window{user="hello"} 806
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 38252.6 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1277686
telemt_connections_bad_total 182291
telemt_connections_current 3167
telemt_connections_me_current 3167
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 26720
telemt_upstream_connect_attempt_total 17835
telemt_upstream_connect_success_total 17676
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 17820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_reconnect_attempts_total 1614
telemt_me_reconnect_success_total 488
telemt_me_reader_eof_total 501
telemt_me_idle_close_by_peer_total 501
telemt_me_route_drop_no_conn_total 317577
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924279
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 308
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
telemt_me_writers_active_current 128
telemt_desync_total 3870
telemt_desync_full_logged_total 1470
telemt_desync_suppressed_total 2400
telemt_desync_frames_bucket_total{bucket="1_2"} 745
telemt_desync_frames_bucket_total{bucket="3_10"} 1563
telemt_desync_frames_bucket_total{bucket="gt_10"} 1562
telemt_pool_swap_total 40
telemt_pool_force_close_total 956
telemt_me_writer_close_signal_drop_total 60
telemt_me_draining_writers_reap_progress_total 14558
telemt_me_writer_removed_unexpected_total 481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13831
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13602
telemt_me_writer_teardown_success_total{mode="normal"} 15059
telemt_me_writer_teardown_noop_total 14558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.069013
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 60
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 409
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 921894
telemt_user_connections_current{user="hello"} 3167
telemt_user_octets_from_client{user="hello"} 15426431436 (14.37 GB)
telemt_user_octets_to_client{user="hello"} 456167939370 (424.84 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1260
telemt_user_unique_ips_recent_window{user="hello"} 356
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 38247.1 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1652745
telemt_connections_bad_total 108322
telemt_connections_current 2309
telemt_connections_me_current 2309
telemt_handshake_timeouts_total 603625
telemt_upstream_connect_attempt_total 16820
telemt_upstream_connect_success_total 16792
telemt_upstream_connect_attempts_per_request{bucket="1"} 16792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 357
telemt_me_reconnect_success_total 248
telemt_me_reader_eof_total 258
telemt_me_idle_close_by_peer_total 258
telemt_me_route_drop_no_conn_total 283864
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 823831
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_shadow_rotate_total 312
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
telemt_me_writers_active_current 44
telemt_desync_total 3772
telemt_desync_full_logged_total 1340
telemt_desync_suppressed_total 2432
telemt_desync_frames_bucket_total{bucket="1_2"} 685
telemt_desync_frames_bucket_total{bucket="3_10"} 1536
telemt_desync_frames_bucket_total{bucket="gt_10"} 1551
telemt_pool_swap_total 42
telemt_pool_force_close_total 975
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 15070
telemt_me_writer_removed_unexpected_total 241
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 896
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14433
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 967
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14095
telemt_me_writer_teardown_success_total{mode="normal"} 15329
telemt_me_writer_teardown_noop_total 15070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.546496
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 820807
telemt_user_connections_current{user="hello"} 2309
telemt_user_octets_from_client{user="hello"} 13291495304 (12.38 GB)
telemt_user_octets_to_client{user="hello"} 420755149496 (391.86 GB)
telemt_user_unique_ips_current{user="hello"} 937
telemt_user_unique_ips_recent_window{user="hello"} 409
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 36238.5 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321092
telemt_connections_bad_total 11707
telemt_connections_current 498
telemt_connections_me_current 498
telemt_handshake_timeouts_total 89487
telemt_upstream_connect_attempt_total 18349
telemt_upstream_connect_success_total 18348
telemt_upstream_connect_attempts_per_request{bucket="1"} 18348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 687
telemt_me_reconnect_success_total 289
telemt_me_reader_eof_total 291
telemt_me_idle_close_by_peer_total 291
telemt_me_route_drop_no_conn_total 75804
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200332
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 317
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
telemt_me_writers_active_current 43
telemt_desync_total 1224
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 657
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 514
telemt_desync_frames_bucket_total{bucket="gt_10"} 478
telemt_pool_swap_total 40
telemt_pool_force_close_total 824
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 48
telemt_me_draining_writers_reap_progress_total 16363
telemt_me_writer_removed_unexpected_total 274
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1149
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15490
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 824
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15539
telemt_me_writer_teardown_success_total{mode="normal"} 16639
telemt_me_writer_teardown_noop_total 16363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33002
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.201101
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33002
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 48
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 200536
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 2254693755 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 86044552721 (80.14 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 38257.0 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1301562
telemt_connections_bad_total 96905
telemt_connections_current 3225
telemt_connections_me_current 3225
telemt_handshake_timeouts_total 35057
telemt_upstream_connect_attempt_total 17262
telemt_upstream_connect_success_total 17182
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 17233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 590
telemt_me_reconnect_success_total 346
telemt_me_reader_eof_total 329
telemt_me_idle_close_by_peer_total 329
telemt_me_route_drop_no_conn_total 288358
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1020327
telemt_me_endpoint_quarantine_total 317
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 309
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
telemt_desync_total 4011
telemt_desync_full_logged_total 1341
telemt_desync_suppressed_total 2670
telemt_desync_frames_bucket_total{bucket="1_2"} 1042
telemt_desync_frames_bucket_total{bucket="3_10"} 1505
telemt_desync_frames_bucket_total{bucket="gt_10"} 1464
telemt_pool_swap_total 42
telemt_pool_force_close_total 991
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 80
telemt_me_draining_writers_reap_progress_total 15594
telemt_me_writer_removed_unexpected_total 330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1092
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14839
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 986
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14603
telemt_me_writer_teardown_success_total{mode="normal"} 15931
telemt_me_writer_teardown_noop_total 15594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.629968
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 80
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1015831
telemt_user_connections_current{user="hello"} 3225
telemt_user_octets_from_client{user="hello"} 16412414644 (15.29 GB)
telemt_user_octets_to_client{user="hello"} 462540884480 (430.77 GB)
telemt_user_unique_ips_current{user="hello"} 1178
telemt_user_unique_ips_recent_window{user="hello"} 415
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 38253.7 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1243960
telemt_connections_bad_total 88835
telemt_connections_current 2970
telemt_connections_me_current 2970
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 32274
telemt_upstream_connect_attempt_total 25804
telemt_upstream_connect_success_total 25621
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 25764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_reconnect_attempts_total 2537
telemt_me_reconnect_success_total 463
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 403
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 292959
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989740
telemt_me_endpoint_quarantine_total 382
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 305
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
telemt_desync_total 3906
telemt_desync_full_logged_total 1222
telemt_desync_suppressed_total 2684
telemt_desync_frames_bucket_total{bucket="1_2"} 1145
telemt_desync_frames_bucket_total{bucket="3_10"} 1433
telemt_desync_frames_bucket_total{bucket="gt_10"} 1328
telemt_pool_swap_total 42
telemt_pool_force_close_total 961
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 14804
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1294
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13947
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13843
telemt_me_writer_teardown_success_total{mode="normal"} 15241
telemt_me_writer_teardown_noop_total 14804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30045
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.502381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30045
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 118
telemt_me_writer_restored_same_endpoint_total 343
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 994424
telemt_user_connections_current{user="hello"} 2970
telemt_user_octets_from_client{user="hello"} 12800184515 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 437783150163 (407.72 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1061
telemt_user_unique_ips_recent_window{user="hello"} 386
```