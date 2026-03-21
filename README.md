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

# Server Metrics 2026-03-21 06:22:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 35219.6 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 714008
telemt_connections_bad_total 41393
telemt_connections_current 1663
telemt_connections_me_current 1663
telemt_handshake_timeouts_total 36770
telemt_upstream_connect_attempt_total 14364
telemt_upstream_connect_success_total 14298
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 14341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 435
telemt_me_reconnect_success_total 231
telemt_me_reader_eof_total 242
telemt_me_idle_close_by_peer_total 242
telemt_me_route_drop_no_conn_total 145792
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533561
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_endpoint_quarantine_total 250
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 291
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
telemt_me_writers_active_current 43
telemt_desync_total 2368
telemt_desync_full_logged_total 853
telemt_desync_suppressed_total 1515
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 948
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 39
telemt_pool_force_close_total 1036
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 12931
telemt_me_writer_removed_unexpected_total 227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 954
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12167
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1033
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11895
telemt_me_writer_teardown_success_total{mode="normal"} 13121
telemt_me_writer_teardown_noop_total 12932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26053
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.155715
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26053
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 208
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 532862
telemt_user_connections_current{user="hello"} 1663
telemt_user_octets_from_client{user="hello"} 6502977540 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 174081770844 (162.13 GB)
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 35220.5 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1871629
telemt_connections_bad_total 222176
telemt_connections_current 3008
telemt_connections_me_current 3008
telemt_handshake_timeouts_total 55720
telemt_upstream_connect_attempt_total 13425
telemt_upstream_connect_success_total 13370
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 13413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 696
telemt_me_reconnect_success_total 253
telemt_me_reader_eof_total 271
telemt_me_idle_close_by_peer_total 271
telemt_me_route_drop_no_conn_total 353284
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1094522
telemt_me_endpoint_quarantine_total 223
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 284
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 4697
telemt_desync_full_logged_total 1638
telemt_desync_suppressed_total 3059
telemt_desync_frames_bucket_total{bucket="1_2"} 971
telemt_desync_frames_bucket_total{bucket="3_10"} 1860
telemt_desync_frames_bucket_total{bucket="gt_10"} 1866
telemt_pool_swap_total 38
telemt_pool_force_close_total 1099
telemt_me_writer_close_signal_drop_total 110
telemt_me_draining_writers_reap_progress_total 12030
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1049
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11225
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1050
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10931
telemt_me_writer_teardown_success_total{mode="normal"} 12274
telemt_me_writer_teardown_noop_total 12030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24304
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.332904
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24304
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 110
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1091871
telemt_user_connections_current{user="hello"} 3008
telemt_user_octets_from_client{user="hello"} 15134604024 (14.10 GB)
telemt_user_octets_to_client{user="hello"} 449283984568 (418.43 GB)
telemt_user_unique_ips_current{user="hello"} 1213
telemt_user_unique_ips_recent_window{user="hello"} 912
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 35217.3 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1219814
telemt_connections_bad_total 155858
telemt_connections_current 3544
telemt_connections_me_current 3544
telemt_handshake_timeouts_total 57662
telemt_upstream_connect_attempt_total 14478
telemt_upstream_connect_success_total 14470
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 406
telemt_me_reconnect_success_total 236
telemt_me_reader_eof_total 246
telemt_me_idle_close_by_peer_total 246
telemt_me_route_drop_no_conn_total 284401
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935718
telemt_me_endpoint_quarantine_total 255
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 283
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
telemt_desync_total 3785
telemt_desync_full_logged_total 1386
telemt_desync_suppressed_total 2399
telemt_desync_frames_bucket_total{bucket="1_2"} 840
telemt_desync_frames_bucket_total{bucket="3_10"} 1468
telemt_desync_frames_bucket_total{bucket="gt_10"} 1477
telemt_pool_swap_total 39
telemt_pool_force_close_total 1023
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 110
telemt_me_draining_writers_reap_progress_total 13140
telemt_me_writer_removed_unexpected_total 227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1013
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12305
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12117
telemt_me_writer_teardown_success_total{mode="normal"} 13318
telemt_me_writer_teardown_noop_total 13143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26461
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.924919
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26461
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 110
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 202
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 933692
telemt_user_connections_current{user="hello"} 3544
telemt_user_octets_from_client{user="hello"} 13072668696 (12.17 GB)
telemt_user_octets_to_client{user="hello"} 414378653160 (385.92 GB)
telemt_user_unique_ips_current{user="hello"} 1320
telemt_user_unique_ips_recent_window{user="hello"} 687
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 35218.4 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1064388
telemt_connections_bad_total 146307
telemt_connections_current 2448
telemt_connections_me_current 2448
telemt_handshake_timeouts_total 53459
telemt_upstream_connect_attempt_total 14598
telemt_upstream_connect_success_total 14510
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 14550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 640
telemt_me_reconnect_success_total 256
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 255
telemt_me_route_drop_no_conn_total 225086
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 712809
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 285
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
telemt_me_writers_active_current 45
telemt_desync_total 3128
telemt_desync_full_logged_total 1176
telemt_desync_suppressed_total 1952
telemt_desync_frames_bucket_total{bucket="1_2"} 674
telemt_desync_frames_bucket_total{bucket="3_10"} 1359
telemt_desync_frames_bucket_total{bucket="gt_10"} 1095
telemt_pool_swap_total 39
telemt_pool_force_close_total 982
telemt_me_writer_close_signal_drop_total 49
telemt_me_draining_writers_reap_progress_total 13075
telemt_me_writer_removed_unexpected_total 244
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 939
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12393
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 964
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12093
telemt_me_writer_teardown_success_total{mode="normal"} 13332
telemt_me_writer_teardown_noop_total 13076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26408
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.906177
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26408
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 49
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 217
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 711561
telemt_user_connections_current{user="hello"} 2448
telemt_user_octets_from_client{user="hello"} 12798315208 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 344275934164 (320.63 GB)
telemt_user_unique_ips_current{user="hello"} 969
telemt_user_unique_ips_recent_window{user="hello"} 319
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 35182.1 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008157
telemt_connections_bad_total 131296
telemt_connections_current 2117
telemt_connections_me_current 2117
telemt_handshake_timeouts_total 37306
telemt_upstream_connect_attempt_total 14971
telemt_upstream_connect_success_total 14962
telemt_upstream_connect_attempts_per_request{bucket="1"} 14962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 245
telemt_me_reconnect_success_total 199
telemt_me_reader_eof_total 206
telemt_me_idle_close_by_peer_total 206
telemt_me_route_drop_no_conn_total 198746
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705095
telemt_me_endpoint_quarantine_total 287
telemt_me_single_endpoint_shadow_rotate_total 281
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 37
telemt_desync_total 3154
telemt_desync_full_logged_total 1230
telemt_desync_suppressed_total 1924
telemt_desync_frames_bucket_total{bucket="1_2"} 751
telemt_desync_frames_bucket_total{bucket="3_10"} 1264
telemt_desync_frames_bucket_total{bucket="gt_10"} 1139
telemt_pool_swap_total 38
telemt_pool_force_close_total 931
telemt_me_writer_close_signal_drop_total 55
telemt_me_draining_writers_reap_progress_total 13557
telemt_me_writer_removed_unexpected_total 188
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 876
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12888
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 928
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12626
telemt_me_writer_teardown_success_total{mode="normal"} 13764
telemt_me_writer_teardown_noop_total 13558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27322
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.395523
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27322
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 55
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 178
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 703715
telemt_user_connections_current{user="hello"} 2117
telemt_user_octets_from_client{user="hello"} 15927989216 (14.83 GB)
telemt_user_octets_to_client{user="hello"} 365792941036 (340.67 GB)
telemt_user_unique_ips_current{user="hello"} 893
telemt_user_unique_ips_recent_window{user="hello"} 324
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 35221.6 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1982257
telemt_connections_bad_total 156186
telemt_connections_current 4359
telemt_connections_me_current 4359
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 140058
telemt_upstream_connect_attempt_total 28281
telemt_upstream_connect_success_total 26909
telemt_upstream_connect_fail_total 870
telemt_upstream_connect_attempts_per_request{bucket="1"} 27779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 427
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 870
telemt_me_reconnect_attempts_total 1745
telemt_me_reconnect_success_total 554
telemt_me_reader_eof_total 371
telemt_me_idle_close_by_peer_total 370
telemt_me_route_drop_no_conn_total 1264538
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1547274
telemt_me_endpoint_quarantine_total 282
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 78
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 78
telemt_me_single_endpoint_shadow_rotate_total 286
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 3775
telemt_desync_full_logged_total 1475
telemt_desync_suppressed_total 2300
telemt_desync_frames_bucket_total{bucket="1_2"} 849
telemt_desync_frames_bucket_total{bucket="3_10"} 1607
telemt_desync_frames_bucket_total{bucket="gt_10"} 1319
telemt_pool_swap_total 38
telemt_pool_force_close_total 1053
telemt_me_writer_close_signal_drop_total 143
telemt_me_draining_writers_reap_progress_total 12137
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1344
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11306
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 987
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11084
telemt_me_writer_teardown_success_total{mode="normal"} 12650
telemt_me_writer_teardown_noop_total 12141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24791
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.950084
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24791
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 143
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 357
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1558707
telemt_user_connections_current{user="hello"} 4359
telemt_user_octets_from_client{user="hello"} 31177589776 (29.04 GB)
telemt_user_octets_to_client{user="hello"} 434461796455 (404.62 GB)
telemt_user_msgs_from_client{user="hello"} 40291
telemt_user_msgs_to_client{user="hello"} 96775
telemt_user_unique_ips_current{user="hello"} 1569
telemt_user_unique_ips_recent_window{user="hello"} 881
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 35188.9 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074289
telemt_connections_bad_total 144847
telemt_connections_current 2473
telemt_connections_me_current 2473
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 22864
telemt_upstream_connect_attempt_total 16491
telemt_upstream_connect_success_total 16346
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 16476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_reconnect_attempts_total 1297
telemt_me_reconnect_success_total 319
telemt_me_reader_eof_total 331
telemt_me_idle_close_by_peer_total 331
telemt_me_route_drop_no_conn_total 254192
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 773466
telemt_me_endpoint_quarantine_total 236
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 285
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 35
telemt_desync_total 3102
telemt_desync_full_logged_total 1180
telemt_desync_suppressed_total 1922
telemt_desync_frames_bucket_total{bucket="1_2"} 574
telemt_desync_frames_bucket_total{bucket="3_10"} 1281
telemt_desync_frames_bucket_total{bucket="gt_10"} 1247
telemt_pool_swap_total 38
telemt_pool_force_close_total 895
telemt_me_writer_close_signal_drop_total 49
telemt_me_draining_writers_reap_progress_total 13533
telemt_me_writer_removed_unexpected_total 311
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1010
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12854
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 889
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12638
telemt_me_writer_teardown_success_total{mode="normal"} 13864
telemt_me_writer_teardown_noop_total 13533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27397
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.005836
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27397
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 49
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 247
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 771177
telemt_user_connections_current{user="hello"} 2473
telemt_user_octets_from_client{user="hello"} 12511912100 (11.65 GB)
telemt_user_octets_to_client{user="hello"} 390232602350 (363.43 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1011
telemt_user_unique_ips_recent_window{user="hello"} 369
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 35183.5 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1355515
telemt_connections_bad_total 84854
telemt_connections_current 2299
telemt_connections_me_current 2299
telemt_handshake_timeouts_total 478751
telemt_upstream_connect_attempt_total 15725
telemt_upstream_connect_success_total 15698
telemt_upstream_connect_attempts_per_request{bucket="1"} 15698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 253
telemt_me_reconnect_attempts_total 310
telemt_me_reconnect_success_total 228
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 212901
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 687671
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_shadow_rotate_total 286
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_warm_current 37
telemt_desync_total 3062
telemt_desync_full_logged_total 1096
telemt_desync_suppressed_total 1966
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 1252
telemt_desync_frames_bucket_total{bucket="gt_10"} 1239
telemt_pool_swap_total 38
telemt_pool_force_close_total 865
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 14052
telemt_me_writer_removed_unexpected_total 221
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 815
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13474
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13187
telemt_me_writer_teardown_success_total{mode="normal"} 14289
telemt_me_writer_teardown_noop_total 14052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28341
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.509805
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28341
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 685446
telemt_user_connections_current{user="hello"} 2299
telemt_user_octets_from_client{user="hello"} 11217558088 (10.45 GB)
telemt_user_octets_to_client{user="hello"} 358334600848 (333.73 GB)
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 337
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 33174.8 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254001
telemt_connections_bad_total 10851
telemt_connections_current 452
telemt_connections_me_current 452
telemt_handshake_timeouts_total 64519
telemt_upstream_connect_attempt_total 17020
telemt_upstream_connect_success_total 17019
telemt_upstream_connect_attempts_per_request{bucket="1"} 17019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 517
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 257
telemt_me_idle_close_by_peer_total 257
telemt_me_route_drop_no_conn_total 61851
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168977
telemt_me_endpoint_quarantine_total 321
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 286
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
telemt_me_writers_active_current 46
telemt_desync_total 1039
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 433
telemt_desync_frames_bucket_total{bucket="gt_10"} 416
telemt_pool_swap_total 36
telemt_pool_force_close_total 713
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 15151
telemt_me_writer_removed_unexpected_total 241
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1044
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14364
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 713
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14438
telemt_me_writer_teardown_success_total{mode="normal"} 15408
telemt_me_writer_teardown_noop_total 15151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30559
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.943721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30559
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 215
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 169219
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 1843322623 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 69875199685 (65.08 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 35193.4 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1106025
telemt_connections_bad_total 83982
telemt_connections_current 2985
telemt_connections_me_current 2985
telemt_handshake_timeouts_total 29163
telemt_upstream_connect_attempt_total 16162
telemt_upstream_connect_success_total 16090
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 16132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 545
telemt_me_reconnect_success_total 317
telemt_me_reader_eof_total 303
telemt_me_idle_close_by_peer_total 303
telemt_me_route_drop_no_conn_total 233842
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 853049
telemt_me_endpoint_quarantine_total 292
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 282
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
telemt_me_writers_warm_current 37
telemt_desync_total 3300
telemt_desync_full_logged_total 1098
telemt_desync_suppressed_total 2202
telemt_desync_frames_bucket_total{bucket="1_2"} 893
telemt_desync_frames_bucket_total{bucket="3_10"} 1248
telemt_desync_frames_bucket_total{bucket="gt_10"} 1159
telemt_pool_swap_total 38
telemt_pool_force_close_total 877
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 67
telemt_me_draining_writers_reap_progress_total 14571
telemt_me_writer_removed_unexpected_total 304
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1001
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13881
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 877
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13694
telemt_me_writer_teardown_success_total{mode="normal"} 14882
telemt_me_writer_teardown_noop_total 14571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.601670
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 67
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 292
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 848820
telemt_user_connections_current{user="hello"} 2985
telemt_user_octets_from_client{user="hello"} 12978673872 (12.09 GB)
telemt_user_octets_to_client{user="hello"} 383202158592 (356.88 GB)
telemt_user_unique_ips_current{user="hello"} 1113
telemt_user_unique_ips_recent_window{user="hello"} 377
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 35190.1 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1051410
telemt_connections_bad_total 66339
telemt_connections_current 2549
telemt_connections_me_current 2549
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 28244
telemt_upstream_connect_attempt_total 24714
telemt_upstream_connect_success_total 24541
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 24676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_reconnect_attempts_total 2387
telemt_me_reconnect_success_total 427
telemt_me_reader_eof_total 366
telemt_me_idle_close_by_peer_total 366
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 240024
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 831971
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 280
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
telemt_me_writers_warm_current 29
telemt_desync_total 3160
telemt_desync_full_logged_total 1012
telemt_desync_suppressed_total 2148
telemt_desync_frames_bucket_total{bucket="1_2"} 956
telemt_desync_frames_bucket_total{bucket="3_10"} 1149
telemt_desync_frames_bucket_total{bucket="gt_10"} 1055
telemt_pool_swap_total 38
telemt_pool_force_close_total 842
telemt_me_writer_close_signal_drop_total 68
telemt_me_draining_writers_reap_progress_total 13815
telemt_me_writer_removed_unexpected_total 380
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1181
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13034
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 827
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12973
telemt_me_writer_teardown_success_total{mode="normal"} 14215
telemt_me_writer_teardown_noop_total 13815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.286508
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 68
telemt_me_refill_failed_total 112
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 836627
telemt_user_connections_current{user="hello"} 2549
telemt_user_octets_from_client{user="hello"} 10559089339 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 367276593575 (342.05 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 350
```