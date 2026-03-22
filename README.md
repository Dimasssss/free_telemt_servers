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

# Server Metrics 2026-03-22 12:23:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 55024.2 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1643059
telemt_connections_bad_total 76790
telemt_connections_current 1679
telemt_connections_me_current 1679
telemt_handshake_timeouts_total 73173
telemt_upstream_connect_attempt_total 20942
telemt_upstream_connect_success_total 20941
telemt_upstream_connect_attempts_per_request{bucket="1"} 20941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 794
telemt_me_reconnect_success_total 341
telemt_me_reader_eof_total 339
telemt_me_idle_close_by_peer_total 339
telemt_me_route_drop_no_conn_total 1103164
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1390305
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 437
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 8225
telemt_desync_full_logged_total 2479
telemt_desync_suppressed_total 5746
telemt_desync_frames_bucket_total{bucket="1_2"} 2333
telemt_desync_frames_bucket_total{bucket="3_10"} 3103
telemt_desync_frames_bucket_total{bucket="gt_10"} 2789
telemt_pool_swap_total 61
telemt_pool_force_close_total 1794
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 278
telemt_me_draining_writers_reap_progress_total 19080
telemt_me_writer_removed_unexpected_total 334
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1346
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17940
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1759
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17286
telemt_me_writer_teardown_success_total{mode="normal"} 19286
telemt_me_writer_teardown_noop_total 19082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38368
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 136.579095
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38368
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 278
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 1387600
telemt_user_connections_current{user="hello"} 1679
telemt_user_octets_from_client{user="hello"} 21626269672 (20.14 GB)
telemt_user_octets_to_client{user="hello"} 411758844396 (383.48 GB)
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 68390.4 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2659837
telemt_connections_bad_total 242437
telemt_connections_current 2429
telemt_connections_me_current 2429
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 61317
telemt_upstream_connect_attempt_total 45170
telemt_upstream_connect_success_total 44645
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 45109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3456
telemt_me_reconnect_success_total 1561
telemt_me_reader_eof_total 1447
telemt_me_idle_close_by_peer_total 1447
telemt_me_route_drop_no_conn_total 2338283
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2086201
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 534
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
telemt_me_writers_active_current 87
telemt_desync_total 8246
telemt_desync_full_logged_total 4650
telemt_desync_suppressed_total 3596
telemt_desync_frames_bucket_total{bucket="1_2"} 1924
telemt_desync_frames_bucket_total{bucket="3_10"} 3207
telemt_desync_frames_bucket_total{bucket="gt_10"} 3115
telemt_pool_swap_total 67
telemt_pool_force_close_total 1890
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 27255
telemt_me_writer_removed_unexpected_total 1407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3001
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25661
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25365
telemt_me_writer_teardown_success_total{mode="normal"} 28662
telemt_me_writer_teardown_noop_total 27255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55917
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.385837
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55917
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1304
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 2097992
telemt_user_connections_current{user="hello"} 2429
telemt_user_octets_from_client{user="hello"} 26019473895 (24.23 GB)
telemt_user_octets_to_client{user="hello"} 511742075594 (476.60 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1423
telemt_user_unique_ips_recent_window{user="hello"} 587
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 143250.2 (39h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12805327
telemt_connections_bad_total 1119546
telemt_connections_current 5280
telemt_connections_me_current 5280
telemt_handshake_timeouts_total 333062
telemt_upstream_connect_attempt_total 52235
telemt_upstream_connect_success_total 52155
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28329
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2369
telemt_me_reconnect_success_total 1217
telemt_me_reader_eof_total 1183
telemt_me_idle_close_by_peer_total 1182
telemt_me_route_drop_no_conn_total 10454244
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10233645
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1066
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
telemt_me_writers_active_current 41
telemt_desync_total 42075
telemt_desync_full_logged_total 13458
telemt_desync_suppressed_total 28617
telemt_desync_frames_bucket_total{bucket="1_2"} 9498
telemt_desync_frames_bucket_total{bucket="3_10"} 16409
telemt_desync_frames_bucket_total{bucket="gt_10"} 16168
telemt_pool_swap_total 154
telemt_pool_force_close_total 5227
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 828
telemt_me_draining_writers_reap_progress_total 47613
telemt_me_writer_removed_unexpected_total 1142
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4133
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43990
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4812
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 415
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42386
telemt_me_writer_teardown_success_total{mode="normal"} 48123
telemt_me_writer_teardown_noop_total 47661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95784
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 225.621787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95784
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 828
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 1057
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 10222139
telemt_user_connections_current{user="hello"} 5280
telemt_user_octets_from_client{user="hello"} 151711215580 (141.29 GB)
telemt_user_octets_to_client{user="hello"} 2853735742940 (2.60 TB)
telemt_user_unique_ips_current{user="hello"} 2166
telemt_user_unique_ips_recent_window{user="hello"} 775
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 143251.6 (39h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9693502
telemt_connections_bad_total 884990
telemt_connections_current 5914
telemt_connections_me_current 5914
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 292221
telemt_upstream_connect_attempt_total 78552
telemt_upstream_connect_success_total 77424
telemt_upstream_connect_fail_total 814
telemt_upstream_connect_attempts_per_request{bucket="1"} 78238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3671
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 814
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3330
telemt_me_reconnect_success_total 1356
telemt_me_reader_eof_total 1240
telemt_me_idle_close_by_peer_total 1240
telemt_me_route_drop_no_conn_total 3889396
telemt_me_route_drop_channel_closed_total 400
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7227276
telemt_me_endpoint_quarantine_total 903
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1091
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
telemt_me_writers_active_current 44
telemt_desync_total 32609
telemt_desync_full_logged_total 11035
telemt_desync_suppressed_total 21574
telemt_desync_frames_bucket_total{bucket="1_2"} 8050
telemt_desync_frames_bucket_total{bucket="3_10"} 12543
telemt_desync_frames_bucket_total{bucket="gt_10"} 12016
telemt_pool_swap_total 154
telemt_pool_force_close_total 4675
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 45870
telemt_me_writer_removed_unexpected_total 1272
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4086
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42923
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4296
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41195
telemt_me_writer_teardown_success_total{mode="normal"} 47009
telemt_me_writer_teardown_noop_total 45881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92890
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 83.004131
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92890
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1157
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 7167824
telemt_user_connections_current{user="hello"} 5914
telemt_user_octets_from_client{user="hello"} 185091363853 (172.38 GB)
telemt_user_octets_to_client{user="hello"} 3257997024586 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2230
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 143215.8 (39h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9131773
telemt_connections_bad_total 764521
telemt_connections_current 2717
telemt_connections_me_current 2717
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 289494
telemt_upstream_connect_attempt_total 63819
telemt_upstream_connect_success_total 63064
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 63226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1963
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3866
telemt_me_reconnect_success_total 1662
telemt_me_reader_eof_total 1497
telemt_me_idle_close_by_peer_total 1496
telemt_me_route_drop_no_conn_total 3976663
telemt_me_route_drop_channel_closed_total 279
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6877263
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1049
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 39
telemt_me_writers_warm_current 6
telemt_desync_total 32293
telemt_desync_full_logged_total 10801
telemt_desync_suppressed_total 21492
telemt_desync_frames_bucket_total{bucket="1_2"} 8110
telemt_desync_frames_bucket_total{bucket="3_10"} 12401
telemt_desync_frames_bucket_total{bucket="gt_10"} 11782
telemt_pool_swap_total 149
telemt_pool_force_close_total 4633
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 602
telemt_me_draining_writers_reap_progress_total 46594
telemt_me_writer_removed_unexpected_total 1578
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4521
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43572
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4154
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 479
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41961
telemt_me_writer_teardown_success_total{mode="normal"} 48093
telemt_me_writer_teardown_noop_total 46660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94753
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3091.991911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94753
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 602
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1449
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 52
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 6869316
telemt_user_connections_current{user="hello"} 2717
telemt_user_octets_from_client{user="hello"} 166205787325 (154.79 GB)
telemt_user_octets_to_client{user="hello"} 2940368398505 (2.67 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 829
telemt_user_unique_ips_recent_window{user="hello"} 1088
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 13495.7 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5711444
telemt_connections_bad_total 339158
telemt_connections_current 6815
telemt_connections_me_current 6815
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 91642
telemt_upstream_connect_attempt_total 23992
telemt_upstream_connect_success_total 22923
telemt_upstream_connect_fail_total 836
telemt_upstream_connect_attempts_per_request{bucket="1"} 23759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4625
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 836
telemt_me_keepalive_timeout_total 521
telemt_me_reconnect_attempts_total 2297
telemt_me_reconnect_success_total 359
telemt_me_reader_eof_total 230
telemt_me_idle_close_by_peer_total 230
telemt_me_route_drop_no_conn_total 13459095
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4783406
telemt_me_endpoint_quarantine_total 86
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 109
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
telemt_desync_total 7267
telemt_desync_full_logged_total 1856
telemt_desync_suppressed_total 5411
telemt_desync_frames_bucket_total{bucket="1_2"} 1317
telemt_desync_frames_bucket_total{bucket="3_10"} 2905
telemt_desync_frames_bucket_total{bucket="gt_10"} 3045
telemt_pool_swap_total 12
telemt_pool_force_close_total 505
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 3486
telemt_me_writer_removed_unexpected_total 318
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 600
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3161
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2981
telemt_me_writer_teardown_success_total{mode="normal"} 3761
telemt_me_writer_teardown_noop_total 3489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7250
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.762963
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7250
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 4796928
telemt_user_connections_current{user="hello"} 6815
telemt_user_octets_from_client{user="hello"} 26476287746 (24.66 GB)
telemt_user_octets_to_client{user="hello"} 139846271031 (130.24 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2423
telemt_user_unique_ips_recent_window{user="hello"} 1307
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 143222.5 (39h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8891083
telemt_connections_bad_total 753933
telemt_connections_current 3558
telemt_connections_me_current 3558
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 189185
telemt_upstream_connect_attempt_total 88434
telemt_upstream_connect_success_total 87560
telemt_upstream_connect_fail_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 88312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 752
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71103
telemt_me_reconnect_success_total 2363
telemt_me_reader_eof_total 2106
telemt_me_idle_close_by_peer_total 2105
telemt_me_route_drop_no_conn_total 4154924
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7021498
telemt_me_endpoint_quarantine_total 958
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1070
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
telemt_me_writers_active_current 41
telemt_desync_total 35858
telemt_desync_full_logged_total 12354
telemt_desync_suppressed_total 23504
telemt_desync_frames_bucket_total{bucket="1_2"} 7322
telemt_desync_frames_bucket_total{bucket="3_10"} 13782
telemt_desync_frames_bucket_total{bucket="gt_10"} 14754
telemt_pool_swap_total 147
telemt_pool_force_close_total 4301
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 521
telemt_me_draining_writers_reap_progress_total 49230
telemt_me_writer_removed_unexpected_total 2134
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5190
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46200
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 593
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44929
telemt_me_writer_teardown_success_total{mode="normal"} 51390
telemt_me_writer_teardown_noop_total 49231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100621
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.025719
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100621
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 521
telemt_me_refill_failed_total 4244
telemt_me_writer_restored_same_endpoint_total 1985
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 7024121
telemt_user_connections_current{user="hello"} 3558
telemt_user_octets_from_client{user="hello"} 166074168379 (154.67 GB)
telemt_user_octets_to_client{user="hello"} 2717425658617 (2.47 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1357
telemt_user_unique_ips_recent_window{user="hello"} 1300
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 80058.5 (22h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8418879
telemt_connections_bad_total 297644
telemt_connections_current 5360
telemt_connections_me_current 5360
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3529627
telemt_upstream_connect_attempt_total 40577
telemt_upstream_connect_success_total 40287
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 40570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_reconnect_attempts_total 47844
telemt_me_reconnect_success_total 1398
telemt_me_reader_eof_total 1068
telemt_me_idle_close_by_peer_total 1068
telemt_me_route_drop_no_conn_total 2890633
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4094209
telemt_me_endpoint_quarantine_total 533
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 605
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
telemt_me_writers_active_current 88
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 22595
telemt_desync_full_logged_total 7539
telemt_desync_suppressed_total 15056
telemt_desync_frames_bucket_total{bucket="1_2"} 4633
telemt_desync_frames_bucket_total{bucket="3_10"} 8782
telemt_desync_frames_bucket_total{bucket="gt_10"} 9180
telemt_pool_swap_total 83
telemt_pool_force_close_total 2550
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 28078
telemt_me_writer_removed_unexpected_total 1133
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2527
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26712
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2186
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 364
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25528
telemt_me_writer_teardown_success_total{mode="normal"} 29239
telemt_me_writer_teardown_noop_total 28085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57324
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.737449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57324
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1250
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4090928
telemt_user_connections_current{user="hello"} 5360
telemt_user_octets_from_client{user="hello"} 92237791828 (85.90 GB)
telemt_user_octets_to_client{user="hello"} 1608943094970 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2109
telemt_user_unique_ips_recent_window{user="hello"} 1179
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 61029.2 (16h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678784
telemt_connections_bad_total 7508
telemt_connections_current 1080
telemt_connections_me_current 1080
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13371
telemt_upstream_connect_attempt_total 31398
telemt_upstream_connect_success_total 31321
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 31387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 1392
telemt_me_reconnect_success_total 601
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 226703
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612729
telemt_me_endpoint_quarantine_total 556
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 511
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
telemt_desync_total 3377
telemt_desync_full_logged_total 992
telemt_desync_suppressed_total 2385
telemt_desync_frames_bucket_total{bucket="1_2"} 842
telemt_desync_frames_bucket_total{bucket="3_10"} 1340
telemt_desync_frames_bucket_total{bucket="gt_10"} 1195
telemt_pool_swap_total 64
telemt_pool_force_close_total 1569
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 25669
telemt_me_writer_removed_unexpected_total 563
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1947
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24304
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1492
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24100
telemt_me_writer_teardown_success_total{mode="normal"} 26251
telemt_me_writer_teardown_noop_total 25671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51922
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.787952
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51922
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 523
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 614494
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 11821399013 (11.01 GB)
telemt_user_octets_to_client{user="hello"} 294925042099 (274.67 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 143226.9 (39h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10809821
telemt_connections_bad_total 1254380
telemt_connections_current 5544
telemt_connections_me_current 5544
telemt_handshake_timeouts_total 289949
telemt_upstream_connect_attempt_total 54497
telemt_upstream_connect_success_total 54284
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 54449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2138
telemt_me_reconnect_success_total 1132
telemt_me_reader_eof_total 1095
telemt_me_idle_close_by_peer_total 1095
telemt_me_route_drop_no_conn_total 3293304
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 31
telemt_me_route_drop_queue_full_profile_total{profile="high"} 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8105142
telemt_me_endpoint_quarantine_total 994
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1076
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
telemt_me_writers_active_current 42
telemt_desync_total 33108
telemt_desync_full_logged_total 10879
telemt_desync_suppressed_total 22229
telemt_desync_frames_bucket_total{bucket="1_2"} 7994
telemt_desync_frames_bucket_total{bucket="3_10"} 12200
telemt_desync_frames_bucket_total{bucket="gt_10"} 12914
telemt_pool_swap_total 159
telemt_pool_force_close_total 4319
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 541
telemt_me_draining_writers_reap_progress_total 49090
telemt_me_writer_removed_unexpected_total 1051
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3997
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46179
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4175
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44771
telemt_me_writer_teardown_success_total{mode="normal"} 50176
telemt_me_writer_teardown_noop_total 49092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99268
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.432915
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99268
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 541
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 989
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 8076391
telemt_user_connections_current{user="hello"} 5544
telemt_user_octets_from_client{user="hello"} 155279324708 (144.62 GB)
telemt_user_octets_to_client{user="hello"} 3689416872812 (3.36 TB)
telemt_user_unique_ips_current{user="hello"} 1938
telemt_user_unique_ips_recent_window{user="hello"} 862
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 143223.9 (39h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9432016
telemt_connections_bad_total 1064401
telemt_connections_current 5236
telemt_connections_me_current 5236
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 244144
telemt_upstream_connect_attempt_total 79533
telemt_upstream_connect_success_total 78952
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 79457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1989
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_reconnect_attempts_total 7014
telemt_me_reconnect_success_total 1751
telemt_me_reader_eof_total 1580
telemt_me_idle_close_by_peer_total 1580
telemt_me_seq_mismatch_total 69
telemt_me_route_drop_no_conn_total 3947099
telemt_me_route_drop_channel_closed_total 298
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7242730
telemt_me_endpoint_quarantine_total 1096
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1080
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_warm_current 35
telemt_desync_total 32404
telemt_desync_full_logged_total 10607
telemt_desync_suppressed_total 21797
telemt_desync_frames_bucket_total{bucket="1_2"} 8032
telemt_desync_frames_bucket_total{bucket="3_10"} 12047
telemt_desync_frames_bucket_total{bucket="gt_10"} 12325
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 529
telemt_me_draining_writers_reap_progress_total 48011
telemt_me_writer_removed_unexpected_total 1602
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4803
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44875
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43832
telemt_me_writer_teardown_success_total{mode="normal"} 49678
telemt_me_writer_teardown_noop_total 48015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.218002
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 529
telemt_me_refill_failed_total 297
telemt_me_writer_restored_same_endpoint_total 1399
telemt_me_writer_restored_fallback_total 93
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 7250609
telemt_user_connections_current{user="hello"} 5236
telemt_user_octets_from_client{user="hello"} 128416075533 (119.60 GB)
telemt_user_octets_to_client{user="hello"} 2913011270471 (2.65 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2175
telemt_user_unique_ips_recent_window{user="hello"} 702
```