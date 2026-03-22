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

# Server Metrics 2026-03-22 11:01:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 50117.8 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1369967
telemt_connections_bad_total 70148
telemt_connections_current 1867
telemt_connections_me_current 1867
telemt_handshake_timeouts_total 62672
telemt_upstream_connect_attempt_total 19285
telemt_upstream_connect_success_total 19284
telemt_upstream_connect_attempts_per_request{bucket="1"} 19284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 643
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 309
telemt_me_idle_close_by_peer_total 309
telemt_me_route_drop_no_conn_total 762098
telemt_me_route_drop_channel_closed_total 373
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1148554
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 354
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 403
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
telemt_me_writers_active_current 45
telemt_desync_total 7393
telemt_desync_full_logged_total 2189
telemt_desync_suppressed_total 5204
telemt_desync_frames_bucket_total{bucket="1_2"} 2144
telemt_desync_frames_bucket_total{bucket="3_10"} 2787
telemt_desync_frames_bucket_total{bucket="gt_10"} 2462
telemt_pool_swap_total 55
telemt_pool_force_close_total 1601
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 226
telemt_me_draining_writers_reap_progress_total 17565
telemt_me_writer_removed_unexpected_total 304
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1233
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16556
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1566
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15964
telemt_me_writer_teardown_success_total{mode="normal"} 17789
telemt_me_writer_teardown_noop_total 17567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 98.779506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 226
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 281
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1146422
telemt_user_connections_current{user="hello"} 1867
telemt_user_octets_from_client{user="hello"} 18573891168 (17.30 GB)
telemt_user_octets_to_client{user="hello"} 359283973060 (334.61 GB)
telemt_user_unique_ips_current{user="hello"} 690
telemt_user_unique_ips_recent_window{user="hello"} 319
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 63483.7 (17h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2196327
telemt_connections_bad_total 179561
telemt_connections_current 1723
telemt_connections_me_current 1723
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 52111
telemt_upstream_connect_attempt_total 43010
telemt_upstream_connect_success_total 42510
telemt_upstream_connect_fail_total 440
telemt_upstream_connect_attempts_per_request{bucket="1"} 42950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 440
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3287
telemt_me_reconnect_success_total 1443
telemt_me_reader_eof_total 1325
telemt_me_idle_close_by_peer_total 1325
telemt_me_route_drop_no_conn_total 1689157
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1724144
telemt_me_endpoint_quarantine_total 549
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 503
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
telemt_me_writers_active_current 40
telemt_desync_total 7076
telemt_desync_full_logged_total 4008
telemt_desync_suppressed_total 3068
telemt_desync_frames_bucket_total{bucket="1_2"} 1612
telemt_desync_frames_bucket_total{bucket="3_10"} 2776
telemt_desync_frames_bucket_total{bucket="gt_10"} 2688
telemt_pool_swap_total 64
telemt_pool_force_close_total 1787
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 25438
telemt_me_writer_removed_unexpected_total 1289
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2801
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23922
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1599
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23651
telemt_me_writer_teardown_success_total{mode="normal"} 26723
telemt_me_writer_teardown_noop_total 25438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52161
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.601807
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52161
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1736082
telemt_user_connections_current{user="hello"} 1723
telemt_user_octets_from_client{user="hello"} 23177490607 (21.59 GB)
telemt_user_octets_to_client{user="hello"} 465463381814 (433.50 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 986
telemt_user_unique_ips_recent_window{user="hello"} 778
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 138343.8 (38h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11709601
telemt_connections_bad_total 1001198
telemt_connections_current 5531
telemt_connections_me_current 5531
telemt_handshake_timeouts_total 315427
telemt_upstream_connect_attempt_total 50417
telemt_upstream_connect_success_total 50337
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27366
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2162
telemt_me_reconnect_success_total 1105
telemt_me_reader_eof_total 1087
telemt_me_idle_close_by_peer_total 1086
telemt_me_route_drop_no_conn_total 8708394
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9336086
telemt_me_endpoint_quarantine_total 883
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1031
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
telemt_desync_total 38725
telemt_desync_full_logged_total 12488
telemt_desync_suppressed_total 26237
telemt_desync_frames_bucket_total{bucket="1_2"} 8724
telemt_desync_frames_bucket_total{bucket="3_10"} 15097
telemt_desync_frames_bucket_total{bucket="gt_10"} 14904
telemt_pool_swap_total 149
telemt_pool_force_close_total 5001
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 781
telemt_me_draining_writers_reap_progress_total 45973
telemt_me_writer_removed_unexpected_total 1047
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3940
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42504
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4667
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40972
telemt_me_writer_teardown_success_total{mode="normal"} 46444
telemt_me_writer_teardown_noop_total 46017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92461
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 210.054147
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92461
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 781
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 962
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 9325293
telemt_user_connections_current{user="hello"} 5531
telemt_user_octets_from_client{user="hello"} 142809426900 (133.00 GB)
telemt_user_octets_to_client{user="hello"} 2737553823700 (2.49 TB)
telemt_user_unique_ips_current{user="hello"} 2017
telemt_user_unique_ips_recent_window{user="hello"} 1009
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 138347.9 (38h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9047141
telemt_connections_bad_total 810139
telemt_connections_current 4975
telemt_connections_me_current 4975
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 276104
telemt_upstream_connect_attempt_total 56958
telemt_upstream_connect_success_total 56382
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 56645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3142
telemt_me_reconnect_success_total 1292
telemt_me_reader_eof_total 1184
telemt_me_idle_close_by_peer_total 1184
telemt_me_route_drop_no_conn_total 3666991
telemt_me_route_drop_channel_closed_total 376
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6742259
telemt_me_endpoint_quarantine_total 871
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1059
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 90
telemt_desync_total 30567
telemt_desync_full_logged_total 10330
telemt_desync_suppressed_total 20237
telemt_desync_frames_bucket_total{bucket="1_2"} 7445
telemt_desync_frames_bucket_total{bucket="3_10"} 11802
telemt_desync_frames_bucket_total{bucket="gt_10"} 11320
telemt_pool_swap_total 148
telemt_pool_force_close_total 4513
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 512
telemt_me_draining_writers_reap_progress_total 44450
telemt_me_writer_removed_unexpected_total 1217
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3916
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41647
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4182
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39937
telemt_me_writer_teardown_success_total{mode="normal"} 45563
telemt_me_writer_teardown_noop_total 44456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 66.270936
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 512
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1110
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 6663878
telemt_user_connections_current{user="hello"} 4975
telemt_user_octets_from_client{user="hello"} 174216735159 (162.25 GB)
telemt_user_octets_to_client{user="hello"} 3068977125294 (2.79 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1989
telemt_user_unique_ips_recent_window{user="hello"} 778
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 138310.6 (38h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8583318
telemt_connections_bad_total 712170
telemt_connections_current 4719
telemt_connections_me_current 4719
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 275904
telemt_upstream_connect_attempt_total 61127
telemt_upstream_connect_success_total 60417
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3661
telemt_me_reconnect_success_total 1493
telemt_me_reader_eof_total 1382
telemt_me_idle_close_by_peer_total 1382
telemt_me_route_drop_no_conn_total 3623001
telemt_me_route_drop_channel_closed_total 243
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6447004
telemt_me_endpoint_quarantine_total 951
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1013
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 29734
telemt_desync_full_logged_total 10128
telemt_desync_suppressed_total 19606
telemt_desync_frames_bucket_total{bucket="1_2"} 7190
telemt_desync_frames_bucket_total{bucket="3_10"} 11478
telemt_desync_frames_bucket_total{bucket="gt_10"} 11066
telemt_pool_swap_total 146
telemt_pool_force_close_total 4462
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 528
telemt_me_draining_writers_reap_progress_total 45202
telemt_me_writer_removed_unexpected_total 1407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4256
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42291
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40740
telemt_me_writer_teardown_success_total{mode="normal"} 46547
telemt_me_writer_teardown_noop_total 45219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91766
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.925526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91766
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 528
telemt_me_refill_failed_total 112
telemt_me_writer_restored_same_endpoint_total 1312
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 6438431
telemt_user_connections_current{user="hello"} 4719
telemt_user_octets_from_client{user="hello"} 159299123559 (148.36 GB)
telemt_user_octets_to_client{user="hello"} 2794032712915 (2.54 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1731
telemt_user_unique_ips_recent_window{user="hello"} 758
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 8588.9 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3677519
telemt_connections_bad_total 241944
telemt_connections_current 6170
telemt_connections_me_current 6170
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 55549
telemt_upstream_connect_attempt_total 22518
telemt_upstream_connect_success_total 21505
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 22333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4605
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_timeout_total 397
telemt_me_reconnect_attempts_total 675
telemt_me_reconnect_success_total 285
telemt_me_reader_eof_total 172
telemt_me_idle_close_by_peer_total 172
telemt_me_route_drop_no_conn_total 8344707
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3055839
telemt_me_endpoint_quarantine_total 62
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 42
telemt_desync_total 4451
telemt_desync_full_logged_total 1171
telemt_desync_suppressed_total 3280
telemt_desync_frames_bucket_total{bucket="1_2"} 811
telemt_desync_frames_bucket_total{bucket="3_10"} 1770
telemt_desync_frames_bucket_total{bucket="gt_10"} 1870
telemt_pool_swap_total 7
telemt_pool_force_close_total 322
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 2264
telemt_me_writer_removed_unexpected_total 263
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2055
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1942
telemt_me_writer_teardown_success_total{mode="normal"} 2498
telemt_me_writer_teardown_noop_total 2267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4765
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.434421
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4765
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 186
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 3071638
telemt_user_connections_current{user="hello"} 6170
telemt_user_octets_from_client{user="hello"} 15627191810 (14.55 GB)
telemt_user_octets_to_client{user="hello"} 90598523327 (84.38 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2090
telemt_user_unique_ips_recent_window{user="hello"} 1803
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 138315.8 (38h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8290319
telemt_connections_bad_total 724234
telemt_connections_current 5122
telemt_connections_me_current 5122
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 170528
telemt_upstream_connect_attempt_total 86479
telemt_upstream_connect_success_total 85621
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 86359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70659
telemt_me_reconnect_success_total 2185
telemt_me_reader_eof_total 1921
telemt_me_idle_close_by_peer_total 1920
telemt_me_route_drop_no_conn_total 3661595
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6544511
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1039
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 51
telemt_desync_total 33222
telemt_desync_full_logged_total 11446
telemt_desync_suppressed_total 21776
telemt_desync_frames_bucket_total{bucket="1_2"} 6805
telemt_desync_frames_bucket_total{bucket="3_10"} 12743
telemt_desync_frames_bucket_total{bucket="gt_10"} 13674
telemt_pool_swap_total 143
telemt_pool_force_close_total 4158
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 47620
telemt_me_writer_removed_unexpected_total 1950
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44680
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 532
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43462
telemt_me_writer_teardown_success_total{mode="normal"} 49595
telemt_me_writer_teardown_noop_total 47621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97216
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.560610
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97216
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 4234
telemt_me_writer_restored_same_endpoint_total 1816
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 6547878
telemt_user_connections_current{user="hello"} 5122
telemt_user_octets_from_client{user="hello"} 157526628207 (146.71 GB)
telemt_user_octets_to_client{user="hello"} 2589007459337 (2.35 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2020
telemt_user_unique_ips_recent_window{user="hello"} 831
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 75151.6 (20h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7375269
telemt_connections_bad_total 277707
telemt_connections_current 4680
telemt_connections_me_current 4680
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3025612
telemt_upstream_connect_attempt_total 38998
telemt_upstream_connect_success_total 38715
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 38991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_reconnect_attempts_total 47698
telemt_me_reconnect_success_total 1335
telemt_me_reader_eof_total 999
telemt_me_idle_close_by_peer_total 999
telemt_me_route_drop_no_conn_total 2275630
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3642135
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 572
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 19744
telemt_desync_full_logged_total 6643
telemt_desync_suppressed_total 13101
telemt_desync_frames_bucket_total{bucket="1_2"} 4006
telemt_desync_frames_bucket_total{bucket="3_10"} 7594
telemt_desync_frames_bucket_total{bucket="gt_10"} 8144
telemt_pool_swap_total 79
telemt_pool_force_close_total 2422
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 239
telemt_me_draining_writers_reap_progress_total 26735
telemt_me_writer_removed_unexpected_total 1067
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2389
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25438
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 355
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24313
telemt_me_writer_teardown_success_total{mode="normal"} 27827
telemt_me_writer_teardown_noop_total 26742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54569
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.318180
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54569
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 239
telemt_me_refill_failed_total 2695
telemt_me_writer_restored_same_endpoint_total 1190
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3640998
telemt_user_connections_current{user="hello"} 4680
telemt_user_octets_from_client{user="hello"} 86272871916 (80.35 GB)
telemt_user_octets_to_client{user="hello"} 1480668967678 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1718
telemt_user_unique_ips_recent_window{user="hello"} 809
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 56122.6 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583847
telemt_connections_bad_total 4494
telemt_connections_current 1012
telemt_connections_me_current 1012
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10852
telemt_upstream_connect_attempt_total 29388
telemt_upstream_connect_success_total 29321
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 29381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 311
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 1281
telemt_me_reconnect_success_total 534
telemt_me_reader_eof_total 525
telemt_me_idle_close_by_peer_total 525
telemt_me_route_drop_no_conn_total 191943
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 528426
telemt_me_endpoint_quarantine_total 510
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 475
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 2823
telemt_desync_full_logged_total 806
telemt_desync_suppressed_total 2017
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 1096
telemt_desync_frames_bucket_total{bucket="gt_10"} 962
telemt_pool_swap_total 59
telemt_pool_force_close_total 1434
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 23920
telemt_me_writer_removed_unexpected_total 508
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1780
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22666
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22486
telemt_me_writer_teardown_success_total{mode="normal"} 24446
telemt_me_writer_teardown_noop_total 23920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48366
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.645707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48366
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 471
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 530343
telemt_user_connections_current{user="hello"} 1012
telemt_user_octets_from_client{user="hello"} 10191223021 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 250058293319 (232.88 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 138320.4 (38h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10065554
telemt_connections_bad_total 1177126
telemt_connections_current 6272
telemt_connections_me_current 6272
telemt_handshake_timeouts_total 267655
telemt_upstream_connect_attempt_total 52987
telemt_upstream_connect_success_total 52784
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 52940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_reconnect_attempts_total 2049
telemt_me_reconnect_success_total 1097
telemt_me_reader_eof_total 1062
telemt_me_idle_close_by_peer_total 1062
telemt_me_route_drop_no_conn_total 2902443
telemt_me_route_drop_channel_closed_total 75
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7506879
telemt_me_endpoint_quarantine_total 975
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1043
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 30463
telemt_desync_full_logged_total 10004
telemt_desync_suppressed_total 20459
telemt_desync_frames_bucket_total{bucket="1_2"} 7454
telemt_desync_frames_bucket_total{bucket="3_10"} 11142
telemt_desync_frames_bucket_total{bucket="gt_10"} 11867
telemt_pool_swap_total 153
telemt_pool_force_close_total 4149
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 503
telemt_me_draining_writers_reap_progress_total 47767
telemt_me_writer_removed_unexpected_total 1020
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3863
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44957
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4029
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43618
telemt_me_writer_teardown_success_total{mode="normal"} 48820
telemt_me_writer_teardown_noop_total 47769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96589
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.360621
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96589
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 503
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 957
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7478639
telemt_user_connections_current{user="hello"} 6272
telemt_user_octets_from_client{user="hello"} 144953383084 (135.00 GB)
telemt_user_octets_to_client{user="hello"} 3474287279592 (3.16 TB)
telemt_user_unique_ips_current{user="hello"} 2224
telemt_user_unique_ips_recent_window{user="hello"} 923
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 138316.6 (38h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8761400
telemt_connections_bad_total 991907
telemt_connections_current 5281
telemt_connections_me_current 5281
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 224235
telemt_upstream_connect_attempt_total 77490
telemt_upstream_connect_success_total 76937
telemt_upstream_connect_fail_total 483
telemt_upstream_connect_attempts_per_request{bucket="1"} 77420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1969
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 483
telemt_me_reconnect_attempts_total 6633
telemt_me_reconnect_success_total 1566
telemt_me_reader_eof_total 1389
telemt_me_idle_close_by_peer_total 1389
telemt_me_seq_mismatch_total 66
telemt_me_route_drop_no_conn_total 3185641
telemt_me_route_drop_channel_closed_total 273
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6699204
telemt_me_endpoint_quarantine_total 1075
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1046
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 29811
telemt_desync_full_logged_total 9815
telemt_desync_suppressed_total 19996
telemt_desync_frames_bucket_total{bucket="1_2"} 7353
telemt_desync_frames_bucket_total{bucket="3_10"} 11037
telemt_desync_frames_bucket_total{bucket="gt_10"} 11421
telemt_pool_swap_total 150
telemt_pool_force_close_total 4082
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 507
telemt_me_draining_writers_reap_progress_total 46452
telemt_me_writer_removed_unexpected_total 1407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4524
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43399
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3780
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42370
telemt_me_writer_teardown_success_total{mode="normal"} 47923
telemt_me_writer_teardown_noop_total 46456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94379
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.786751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94379
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 507
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1219
telemt_me_writer_restored_fallback_total 90
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 6707164
telemt_user_connections_current{user="hello"} 5281
telemt_user_octets_from_client{user="hello"} 121412812425 (113.07 GB)
telemt_user_octets_to_client{user="hello"} 2801364747363 (2.55 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1982
telemt_user_unique_ips_recent_window{user="hello"} 767
```