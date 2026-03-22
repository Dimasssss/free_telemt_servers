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

# Server Metrics 2026-03-22 11:06:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 50425.0 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1382855
telemt_connections_bad_total 70504
telemt_connections_current 1654
telemt_connections_me_current 1654
telemt_handshake_timeouts_total 63370
telemt_upstream_connect_attempt_total 19385
telemt_upstream_connect_success_total 19384
telemt_upstream_connect_attempts_per_request{bucket="1"} 19384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 649
telemt_me_reconnect_success_total 318
telemt_me_reader_eof_total 313
telemt_me_idle_close_by_peer_total 313
telemt_me_route_drop_no_conn_total 768052
telemt_me_route_drop_channel_closed_total 380
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1159688
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 3
telemt_desync_total 7427
telemt_desync_full_logged_total 2204
telemt_desync_suppressed_total 5223
telemt_desync_frames_bucket_total{bucket="1_2"} 2151
telemt_desync_frames_bucket_total{bucket="3_10"} 2796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2480
telemt_pool_swap_total 55
telemt_pool_force_close_total 1601
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 227
telemt_me_draining_writers_reap_progress_total 17630
telemt_me_writer_removed_unexpected_total 308
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1240
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16618
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1566
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16029
telemt_me_writer_teardown_success_total{mode="normal"} 17858
telemt_me_writer_teardown_noop_total 17632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35490
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.247015
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35490
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 227
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 285
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1157554
telemt_user_connections_current{user="hello"} 1654
telemt_user_octets_from_client{user="hello"} 18711162808 (17.43 GB)
telemt_user_octets_to_client{user="hello"} 363166486420 (338.23 GB)
telemt_user_unique_ips_current{user="hello"} 639
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 63791.4 (17h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2229337
telemt_connections_bad_total 182234
telemt_connections_current 1698
telemt_connections_me_current 1698
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 52470
telemt_upstream_connect_attempt_total 43069
telemt_upstream_connect_success_total 42569
telemt_upstream_connect_fail_total 440
telemt_upstream_connect_attempts_per_request{bucket="1"} 43009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 440
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3289
telemt_me_reconnect_success_total 1444
telemt_me_reader_eof_total 1326
telemt_me_idle_close_by_peer_total 1326
telemt_me_route_drop_no_conn_total 1741217
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1752179
telemt_me_endpoint_quarantine_total 550
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 504
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
telemt_desync_total 7162
telemt_desync_full_logged_total 4052
telemt_desync_suppressed_total 3110
telemt_desync_frames_bucket_total{bucket="1_2"} 1633
telemt_desync_frames_bucket_total{bucket="3_10"} 2816
telemt_desync_frames_bucket_total{bucket="gt_10"} 2713
telemt_pool_swap_total 64
telemt_pool_force_close_total 1787
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 25487
telemt_me_writer_removed_unexpected_total 1290
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2803
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23970
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1599
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23700
telemt_me_writer_teardown_success_total{mode="normal"} 26773
telemt_me_writer_teardown_noop_total 25487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52260
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.604325
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52260
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 1195
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1764117
telemt_user_connections_current{user="hello"} 1698
telemt_user_octets_from_client{user="hello"} 23307213411 (21.71 GB)
telemt_user_octets_to_client{user="hello"} 467521677006 (435.41 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1036
telemt_user_unique_ips_recent_window{user="hello"} 698
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 138652.1 (38h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11805840
telemt_connections_bad_total 1010116
telemt_connections_current 5453
telemt_connections_me_current 5453
telemt_handshake_timeouts_total 316397
telemt_upstream_connect_attempt_total 50490
telemt_upstream_connect_success_total 50410
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2162
telemt_me_reconnect_success_total 1105
telemt_me_reader_eof_total 1087
telemt_me_idle_close_by_peer_total 1086
telemt_me_route_drop_no_conn_total 8917535
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9418686
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
telemt_me_writers_warm_current 19
telemt_desync_total 38925
telemt_desync_full_logged_total 12544
telemt_desync_suppressed_total 26381
telemt_desync_frames_bucket_total{bucket="1_2"} 8781
telemt_desync_frames_bucket_total{bucket="3_10"} 15181
telemt_desync_frames_bucket_total{bucket="gt_10"} 14963
telemt_pool_swap_total 149
telemt_pool_force_close_total 5001
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 781
telemt_me_draining_writers_reap_progress_total 46025
telemt_me_writer_removed_unexpected_total 1047
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3941
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42555
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4667
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41024
telemt_me_writer_teardown_success_total{mode="normal"} 46496
telemt_me_writer_teardown_noop_total 46069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92565
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 210.077487
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92565
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 781
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 962
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 9407883
telemt_user_connections_current{user="hello"} 5453
telemt_user_octets_from_client{user="hello"} 143264905720 (133.43 GB)
telemt_user_octets_to_client{user="hello"} 2743723668000 (2.50 TB)
telemt_user_unique_ips_current{user="hello"} 2087
telemt_user_unique_ips_recent_window{user="hello"} 1062
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 138652.6 (38h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9081505
telemt_connections_bad_total 812367
telemt_connections_current 4642
telemt_connections_me_current 4642
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 277285
telemt_upstream_connect_attempt_total 57101
telemt_upstream_connect_success_total 56523
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 56787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3143
telemt_me_reconnect_success_total 1293
telemt_me_reader_eof_total 1185
telemt_me_idle_close_by_peer_total 1185
telemt_me_route_drop_no_conn_total 3686445
telemt_me_route_drop_channel_closed_total 381
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6769197
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
telemt_me_writers_warm_current 15
telemt_desync_total 30704
telemt_desync_full_logged_total 10359
telemt_desync_suppressed_total 20345
telemt_desync_frames_bucket_total{bucket="1_2"} 7506
telemt_desync_frames_bucket_total{bucket="3_10"} 11839
telemt_desync_frames_bucket_total{bucket="gt_10"} 11359
telemt_pool_swap_total 148
telemt_pool_force_close_total 4513
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 512
telemt_me_draining_writers_reap_progress_total 44567
telemt_me_writer_removed_unexpected_total 1218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41761
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4182
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40054
telemt_me_writer_teardown_success_total{mode="normal"} 45681
telemt_me_writer_teardown_noop_total 44573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 66.388898
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 512
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1111
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 6690818
telemt_user_connections_current{user="hello"} 4642
telemt_user_octets_from_client{user="hello"} 174982144203 (162.96 GB)
telemt_user_octets_to_client{user="hello"} 3081238152046 (2.80 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1889
telemt_user_unique_ips_recent_window{user="hello"} 679
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 138618.4 (38h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8620770
telemt_connections_bad_total 714177
telemt_connections_current 4325
telemt_connections_me_current 4325
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 276789
telemt_upstream_connect_attempt_total 61172
telemt_upstream_connect_success_total 60462
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3662
telemt_me_reconnect_success_total 1494
telemt_me_reader_eof_total 1383
telemt_me_idle_close_by_peer_total 1383
telemt_me_route_drop_no_conn_total 3645727
telemt_me_route_drop_channel_closed_total 246
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6476974
telemt_me_endpoint_quarantine_total 951
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1014
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
telemt_desync_total 29854
telemt_desync_full_logged_total 10171
telemt_desync_suppressed_total 19683
telemt_desync_frames_bucket_total{bucket="1_2"} 7226
telemt_desync_frames_bucket_total{bucket="3_10"} 11523
telemt_desync_frames_bucket_total{bucket="gt_10"} 11105
telemt_pool_swap_total 146
telemt_pool_force_close_total 4462
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 528
telemt_me_draining_writers_reap_progress_total 45234
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4258
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42322
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40772
telemt_me_writer_teardown_success_total{mode="normal"} 46580
telemt_me_writer_teardown_noop_total 45251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91831
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.946865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91831
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 528
telemt_me_refill_failed_total 112
telemt_me_writer_restored_same_endpoint_total 1313
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 6468403
telemt_user_connections_current{user="hello"} 4325
telemt_user_octets_from_client{user="hello"} 159899206307 (148.92 GB)
telemt_user_octets_to_client{user="hello"} 2803765914911 (2.55 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1690
telemt_user_unique_ips_recent_window{user="hello"} 620
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 8896.4 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3805133
telemt_connections_bad_total 248596
telemt_connections_current 6835
telemt_connections_me_current 6835
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 57102
telemt_upstream_connect_attempt_total 22592
telemt_upstream_connect_success_total 21570
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 22398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4608
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_timeout_total 397
telemt_me_reconnect_attempts_total 675
telemt_me_reconnect_success_total 286
telemt_me_reader_eof_total 172
telemt_me_idle_close_by_peer_total 172
telemt_me_route_drop_no_conn_total 8631142
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3166408
telemt_me_endpoint_quarantine_total 62
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 74
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
telemt_desync_total 4535
telemt_desync_full_logged_total 1202
telemt_desync_suppressed_total 3333
telemt_desync_frames_bucket_total{bucket="1_2"} 822
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 1906
telemt_pool_swap_total 7
telemt_pool_force_close_total 322
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 2325
telemt_me_writer_removed_unexpected_total 263
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2115
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2003
telemt_me_writer_teardown_success_total{mode="normal"} 2559
telemt_me_writer_teardown_noop_total 2328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4887
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.494684
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4887
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 186
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 3182087
telemt_user_connections_current{user="hello"} 6835
telemt_user_octets_from_client{user="hello"} 16610259546 (15.47 GB)
telemt_user_octets_to_client{user="hello"} 93462429307 (87.04 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2396
telemt_user_unique_ips_recent_window{user="hello"} 1302
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 138623.6 (38h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8326236
telemt_connections_bad_total 726765
telemt_connections_current 4897
telemt_connections_me_current 4897
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 171859
telemt_upstream_connect_attempt_total 86559
telemt_upstream_connect_success_total 85701
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 86439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70659
telemt_me_reconnect_success_total 2185
telemt_me_reader_eof_total 1921
telemt_me_idle_close_by_peer_total 1920
telemt_me_route_drop_no_conn_total 3687121
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6573976
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1040
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
telemt_desync_total 33456
telemt_desync_full_logged_total 11516
telemt_desync_suppressed_total 21940
telemt_desync_frames_bucket_total{bucket="1_2"} 6869
telemt_desync_frames_bucket_total{bucket="3_10"} 12820
telemt_desync_frames_bucket_total{bucket="gt_10"} 13767
telemt_pool_swap_total 143
telemt_pool_force_close_total 4158
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 47694
telemt_me_writer_removed_unexpected_total 1950
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4917
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44752
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 532
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43536
telemt_me_writer_teardown_success_total{mode="normal"} 49669
telemt_me_writer_teardown_noop_total 47695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97364
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.561715
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97364
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 4234
telemt_me_writer_restored_same_endpoint_total 1816
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 6577366
telemt_user_connections_current{user="hello"} 4897
telemt_user_octets_from_client{user="hello"} 157990366559 (147.14 GB)
telemt_user_octets_to_client{user="hello"} 2597166338653 (2.36 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1991
telemt_user_unique_ips_recent_window{user="hello"} 759
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 75459.4 (20h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7449270
telemt_connections_bad_total 279169
telemt_connections_current 4632
telemt_connections_me_current 4632
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3057078
telemt_upstream_connect_attempt_total 39051
telemt_upstream_connect_success_total 38768
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 39044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_reconnect_attempts_total 47698
telemt_me_reconnect_success_total 1335
telemt_me_reader_eof_total 999
telemt_me_idle_close_by_peer_total 999
telemt_me_route_drop_no_conn_total 2357288
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3677308
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 573
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
telemt_desync_total 19941
telemt_desync_full_logged_total 6697
telemt_desync_suppressed_total 13244
telemt_desync_frames_bucket_total{bucket="1_2"} 4045
telemt_desync_frames_bucket_total{bucket="3_10"} 7700
telemt_desync_frames_bucket_total{bucket="gt_10"} 8196
telemt_pool_swap_total 79
telemt_pool_force_close_total 2422
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 239
telemt_me_draining_writers_reap_progress_total 26788
telemt_me_writer_removed_unexpected_total 1067
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2391
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25489
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 355
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24366
telemt_me_writer_teardown_success_total{mode="normal"} 27880
telemt_me_writer_teardown_noop_total 26795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54675
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.320009
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54675
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 239
telemt_me_refill_failed_total 2695
telemt_me_writer_restored_same_endpoint_total 1190
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3675922
telemt_user_connections_current{user="hello"} 4632
telemt_user_octets_from_client{user="hello"} 86666105920 (80.71 GB)
telemt_user_octets_to_client{user="hello"} 1488311114094 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1804
telemt_user_unique_ips_recent_window{user="hello"} 706
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 56430.2 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590357
telemt_connections_bad_total 4695
telemt_connections_current 1035
telemt_connections_me_current 1035
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10968
telemt_upstream_connect_attempt_total 29477
telemt_upstream_connect_success_total 29410
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 29470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 312
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 1281
telemt_me_reconnect_success_total 534
telemt_me_reader_eof_total 525
telemt_me_idle_close_by_peer_total 525
telemt_me_route_drop_no_conn_total 194237
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534083
telemt_me_endpoint_quarantine_total 510
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 477
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
telemt_desync_total 2880
telemt_desync_full_logged_total 821
telemt_desync_suppressed_total 2059
telemt_desync_frames_bucket_total{bucket="1_2"} 773
telemt_desync_frames_bucket_total{bucket="3_10"} 1116
telemt_desync_frames_bucket_total{bucket="gt_10"} 991
telemt_pool_swap_total 59
telemt_pool_force_close_total 1434
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 24008
telemt_me_writer_removed_unexpected_total 508
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1784
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22750
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22574
telemt_me_writer_teardown_success_total{mode="normal"} 24534
telemt_me_writer_teardown_noop_total 24008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48542
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.649223
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48542
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 471
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 536001
telemt_user_connections_current{user="hello"} 1035
telemt_user_octets_from_client{user="hello"} 10302386057 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 252491407791 (235.15 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 138628.4 (38h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10107975
telemt_connections_bad_total 1180468
telemt_connections_current 5978
telemt_connections_me_current 5978
telemt_handshake_timeouts_total 268536
telemt_upstream_connect_attempt_total 53045
telemt_upstream_connect_success_total 52842
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 52998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_reconnect_attempts_total 2049
telemt_me_reconnect_success_total 1097
telemt_me_reader_eof_total 1062
telemt_me_idle_close_by_peer_total 1062
telemt_me_route_drop_no_conn_total 2921664
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7541389
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
telemt_me_writers_warm_current 2
telemt_desync_total 30686
telemt_desync_full_logged_total 10082
telemt_desync_suppressed_total 20604
telemt_desync_frames_bucket_total{bucket="1_2"} 7494
telemt_desync_frames_bucket_total{bucket="3_10"} 11233
telemt_desync_frames_bucket_total{bucket="gt_10"} 11959
telemt_pool_swap_total 153
telemt_pool_force_close_total 4149
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 503
telemt_me_draining_writers_reap_progress_total 47822
telemt_me_writer_removed_unexpected_total 1020
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3863
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45012
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4029
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43673
telemt_me_writer_teardown_success_total{mode="normal"} 48875
telemt_me_writer_teardown_noop_total 47824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.364437
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 503
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 957
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7513159
telemt_user_connections_current{user="hello"} 5978
telemt_user_octets_from_client{user="hello"} 145797878900 (135.78 GB)
telemt_user_octets_to_client{user="hello"} 3490035336348 (3.17 TB)
telemt_user_unique_ips_current{user="hello"} 2250
telemt_user_unique_ips_recent_window{user="hello"} 811
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 138624.7 (38h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8808770
telemt_connections_bad_total 998722
telemt_connections_current 5224
telemt_connections_me_current 5224
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 225024
telemt_upstream_connect_attempt_total 77551
telemt_upstream_connect_success_total 76998
telemt_upstream_connect_fail_total 483
telemt_upstream_connect_attempts_per_request{bucket="1"} 77481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1969
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 483
telemt_me_reconnect_attempts_total 6633
telemt_me_reconnect_success_total 1566
telemt_me_reader_eof_total 1389
telemt_me_idle_close_by_peer_total 1389
telemt_me_seq_mismatch_total 66
telemt_me_route_drop_no_conn_total 3234585
telemt_me_route_drop_channel_closed_total 273
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6736258
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
telemt_desync_total 29952
telemt_desync_full_logged_total 9859
telemt_desync_suppressed_total 20093
telemt_desync_frames_bucket_total{bucket="1_2"} 7390
telemt_desync_frames_bucket_total{bucket="3_10"} 11083
telemt_desync_frames_bucket_total{bucket="gt_10"} 11479
telemt_pool_swap_total 150
telemt_pool_force_close_total 4082
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 507
telemt_me_draining_writers_reap_progress_total 46513
telemt_me_writer_removed_unexpected_total 1407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4526
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43458
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3780
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42431
telemt_me_writer_teardown_success_total{mode="normal"} 47984
telemt_me_writer_teardown_noop_total 46517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94501
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.797240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94501
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 507
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1219
telemt_me_writer_restored_fallback_total 90
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 6744223
telemt_user_connections_current{user="hello"} 5224
telemt_user_octets_from_client{user="hello"} 121846066125 (113.48 GB)
telemt_user_octets_to_client{user="hello"} 2809095975775 (2.55 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1987
telemt_user_unique_ips_recent_window{user="hello"} 739
```