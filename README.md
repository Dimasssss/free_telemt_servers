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

# Server Metrics 2026-03-22 06:51:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 35100.9 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 689821
telemt_connections_bad_total 42622
telemt_connections_current 1354
telemt_connections_me_current 1354
telemt_handshake_timeouts_total 33385
telemt_upstream_connect_attempt_total 14305
telemt_upstream_connect_success_total 14304
telemt_upstream_connect_attempts_per_request{bucket="1"} 14304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 373
telemt_me_reconnect_success_total 222
telemt_me_reader_eof_total 218
telemt_me_idle_close_by_peer_total 218
telemt_me_route_drop_no_conn_total 245667
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571511
telemt_me_endpoint_quarantine_total 255
telemt_me_single_endpoint_shadow_rotate_total 288
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 4726
telemt_desync_full_logged_total 1322
telemt_desync_suppressed_total 3404
telemt_desync_frames_bucket_total{bucket="1_2"} 1541
telemt_desync_frames_bucket_total{bucket="3_10"} 1765
telemt_desync_frames_bucket_total{bucket="gt_10"} 1420
telemt_pool_swap_total 38
telemt_pool_force_close_total 1018
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 12946
telemt_me_writer_removed_unexpected_total 215
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 893
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12255
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1007
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11928
telemt_me_writer_teardown_success_total{mode="normal"} 13148
telemt_me_writer_teardown_noop_total 12947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26095
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.325702
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26095
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 203
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 570384
telemt_user_connections_current{user="hello"} 1354
telemt_user_octets_from_client{user="hello"} 8027758268 (7.48 GB)
telemt_user_octets_to_client{user="hello"} 199398992024 (185.70 GB)
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 48467.4 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164317
telemt_connections_bad_total 113543
telemt_connections_current 1422
telemt_connections_me_current 1422
telemt_handshake_timeouts_total 37171
telemt_upstream_connect_attempt_total 25712
telemt_upstream_connect_success_total 25333
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 25661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1912
telemt_me_reconnect_success_total 750
telemt_me_reader_eof_total 655
telemt_me_idle_close_by_peer_total 655
telemt_me_route_drop_no_conn_total 427290
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 880404
telemt_me_endpoint_quarantine_total 442
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 389
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
telemt_me_writers_active_current 45
telemt_desync_total 3724
telemt_desync_full_logged_total 2180
telemt_desync_suppressed_total 1544
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 1440
telemt_desync_frames_bucket_total{bucket="gt_10"} 1502
telemt_pool_swap_total 51
telemt_pool_force_close_total 1358
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 19996
telemt_me_writer_removed_unexpected_total 629
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1756
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18853
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18638
telemt_me_writer_teardown_success_total{mode="normal"} 20609
telemt_me_writer_teardown_noop_total 19996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.142127
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 565
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 882225
telemt_user_connections_current{user="hello"} 1422
telemt_user_octets_from_client{user="hello"} 14185096298 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 327859950923 (305.34 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 903
telemt_user_unique_ips_recent_window{user="hello"} 384
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 123327.2 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8792630
telemt_connections_bad_total 812836
telemt_connections_current 4541
telemt_connections_me_current 4541
telemt_handshake_timeouts_total 277884
telemt_upstream_connect_attempt_total 45637
telemt_upstream_connect_success_total 45559
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1745
telemt_me_reconnect_success_total 907
telemt_me_reader_eof_total 910
telemt_me_idle_close_by_peer_total 910
telemt_me_route_drop_no_conn_total 4794866
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6949609
telemt_me_endpoint_quarantine_total 783
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 926
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 4
telemt_desync_total 29797
telemt_desync_full_logged_total 9870
telemt_desync_suppressed_total 19927
telemt_desync_frames_bucket_total{bucket="1_2"} 6462
telemt_desync_frames_bucket_total{bucket="3_10"} 11602
telemt_desync_frames_bucket_total{bucket="gt_10"} 11733
telemt_pool_swap_total 133
telemt_pool_force_close_total 4395
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 661
telemt_me_draining_writers_reap_progress_total 41662
telemt_me_writer_removed_unexpected_total 875
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3460
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38576
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4131
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 264
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37267
telemt_me_writer_teardown_success_total{mode="normal"} 42036
telemt_me_writer_teardown_noop_total 41706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83742
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 174.797796
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83742
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 661
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 810
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 6940578
telemt_user_connections_current{user="hello"} 4541
telemt_user_octets_from_client{user="hello"} 117407897620 (109.34 GB)
telemt_user_octets_to_client{user="hello"} 2373443281844 (2.16 TB)
telemt_user_unique_ips_current{user="hello"} 1840
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 123328.5 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7249433
telemt_connections_bad_total 639133
telemt_connections_current 3850
telemt_connections_me_current 3850
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 239472
telemt_upstream_connect_attempt_total 49652
telemt_upstream_connect_success_total 49246
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24353
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2612
telemt_me_reconnect_success_total 970
telemt_me_reader_eof_total 937
telemt_me_idle_close_by_peer_total 937
telemt_me_route_drop_no_conn_total 2440460
telemt_me_route_drop_channel_closed_total 299
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5365408
telemt_me_endpoint_quarantine_total 780
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 949
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
telemt_me_writers_active_current 54
telemt_me_writers_warm_current 4
telemt_desync_total 24782
telemt_desync_full_logged_total 8514
telemt_desync_suppressed_total 16268
telemt_desync_frames_bucket_total{bucket="1_2"} 5932
telemt_desync_frames_bucket_total{bucket="3_10"} 9626
telemt_desync_frames_bucket_total{bucket="gt_10"} 9224
telemt_pool_swap_total 134
telemt_pool_force_close_total 3991
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 412
telemt_me_draining_writers_reap_progress_total 40132
telemt_me_writer_removed_unexpected_total 914
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37666
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3766
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36141
telemt_me_writer_teardown_success_total{mode="normal"} 40975
telemt_me_writer_teardown_noop_total 40138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81113
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.311185
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81113
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 412
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 5286621
telemt_user_connections_current{user="hello"} 3850
telemt_user_octets_from_client{user="hello"} 151307057917 (140.92 GB)
telemt_user_octets_to_client{user="hello"} 2558818921159 (2.33 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1566
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 123292.8 (34h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6989713
telemt_connections_bad_total 583054
telemt_connections_current 3090
telemt_connections_me_current 3090
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 234709
telemt_upstream_connect_attempt_total 56077
telemt_upstream_connect_success_total 55461
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 2648
telemt_me_reconnect_success_total 1124
telemt_me_reader_eof_total 1048
telemt_me_idle_close_by_peer_total 1048
telemt_me_route_drop_no_conn_total 2543341
telemt_me_route_drop_channel_closed_total 159
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5201819
telemt_me_endpoint_quarantine_total 876
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 912
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
telemt_desync_total 24674
telemt_desync_full_logged_total 8373
telemt_desync_suppressed_total 16301
telemt_desync_frames_bucket_total{bucket="1_2"} 5981
telemt_desync_frames_bucket_total{bucket="3_10"} 9470
telemt_desync_frames_bucket_total{bucket="gt_10"} 9223
telemt_pool_swap_total 132
telemt_pool_force_close_total 3865
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 432
telemt_me_draining_writers_reap_progress_total 41036
telemt_me_writer_removed_unexpected_total 1038
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3576
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38512
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3609
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37171
telemt_me_writer_teardown_success_total{mode="normal"} 42088
telemt_me_writer_teardown_noop_total 41048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.177539
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 432
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 968
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 5195744
telemt_user_connections_current{user="hello"} 3090
telemt_user_octets_from_client{user="hello"} 140831262511 (131.16 GB)
telemt_user_octets_to_client{user="hello"} 2358656921519 (2.15 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1299
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 123331.8 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22406447
telemt_connections_bad_total 1894013
telemt_connections_current 5394
telemt_connections_me_current 5394
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 671843
telemt_upstream_connect_attempt_total 238416
telemt_upstream_connect_success_total 218798
telemt_upstream_connect_fail_total 17674
telemt_upstream_connect_attempts_per_request{bucket="1"} 236472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17674
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66388
telemt_me_reconnect_success_total 2617
telemt_me_reader_eof_total 1647
telemt_me_idle_close_by_peer_total 1645
telemt_me_route_drop_no_conn_total 42412836
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18010922
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 961
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 966
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 5
telemt_desync_total 34784
telemt_desync_full_logged_total 10453
telemt_desync_suppressed_total 24331
telemt_desync_frames_bucket_total{bucket="1_2"} 7726
telemt_desync_frames_bucket_total{bucket="3_10"} 15346
telemt_desync_frames_bucket_total{bucket="gt_10"} 11712
telemt_pool_swap_total 127
telemt_pool_force_close_total 4025
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 920
telemt_me_draining_writers_reap_progress_total 38605
telemt_me_writer_removed_unexpected_total 2423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5226
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35533
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3450
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 575
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34580
telemt_me_writer_teardown_success_total{mode="normal"} 40759
telemt_me_writer_teardown_noop_total 38635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79394
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 279.160928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79394
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 920
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1780
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 18175760
telemt_user_connections_current{user="hello"} 5394
telemt_user_octets_from_client{user="hello"} 267816657939 (249.42 GB)
telemt_user_octets_to_client{user="hello"} 1385019465694 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 500908
telemt_user_msgs_to_client{user="hello"} 1006528
telemt_user_unique_ips_current{user="hello"} 1960
telemt_user_unique_ips_recent_window{user="hello"} 1019
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 123299.4 (34h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6714504
telemt_connections_bad_total 622822
telemt_connections_current 3578
telemt_connections_me_current 3578
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 139370
telemt_upstream_connect_attempt_total 64706
telemt_upstream_connect_success_total 63965
telemt_upstream_connect_fail_total 635
telemt_upstream_connect_attempts_per_request{bucket="1"} 64600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 635
telemt_me_reconnect_attempts_total 69998
telemt_me_reconnect_success_total 1916
telemt_me_reader_eof_total 1693
telemt_me_idle_close_by_peer_total 1692
telemt_me_route_drop_no_conn_total 2570958
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5247787
telemt_me_endpoint_quarantine_total 826
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 935
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
telemt_me_writers_active_current 44
telemt_desync_total 26273
telemt_desync_full_logged_total 9143
telemt_desync_suppressed_total 17130
telemt_desync_frames_bucket_total{bucket="1_2"} 5244
telemt_desync_frames_bucket_total{bucket="3_10"} 10093
telemt_desync_frames_bucket_total{bucket="gt_10"} 10936
telemt_pool_swap_total 128
telemt_pool_force_close_total 3672
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 433
telemt_me_draining_writers_reap_progress_total 43289
telemt_me_writer_removed_unexpected_total 1724
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4334
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40716
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39617
telemt_me_writer_teardown_success_total{mode="normal"} 45050
telemt_me_writer_teardown_noop_total 43290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88340
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.914352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88340
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 433
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1600
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5239295
telemt_user_connections_current{user="hello"} 3578
telemt_user_octets_from_client{user="hello"} 134785192756 (125.53 GB)
telemt_user_octets_to_client{user="hello"} 2192794288790 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1536
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 60135.3 (16h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4887345
telemt_connections_bad_total 200397
telemt_connections_current 3199
telemt_connections_me_current 3199
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1930429
telemt_upstream_connect_attempt_total 33556
telemt_upstream_connect_success_total 33327
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 33549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_reconnect_attempts_total 46193
telemt_me_reconnect_success_total 1071
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 1201838
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2434531
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 461
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 13016
telemt_desync_full_logged_total 4494
telemt_desync_suppressed_total 8522
telemt_desync_frames_bucket_total{bucket="1_2"} 2564
telemt_desync_frames_bucket_total{bucket="3_10"} 4962
telemt_desync_frames_bucket_total{bucket="gt_10"} 5490
telemt_pool_swap_total 65
telemt_pool_force_close_total 1910
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 21986
telemt_me_writer_removed_unexpected_total 831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1858
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20989
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1691
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 219
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20076
telemt_me_writer_teardown_success_total{mode="normal"} 22847
telemt_me_writer_teardown_noop_total 21988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.776803
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2436496
telemt_user_connections_current{user="hello"} 3199
telemt_user_octets_from_client{user="hello"} 63231594272 (58.89 GB)
telemt_user_octets_to_client{user="hello"} 1081615985686 (1007.33 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1366
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 41105.9 (11h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309187
telemt_connections_bad_total 2130
telemt_connections_current 703
telemt_connections_me_current 703
telemt_handshake_timeouts_total 7208
telemt_upstream_connect_attempt_total 19742
telemt_upstream_connect_success_total 19693
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 19738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 832
telemt_me_reconnect_success_total 283
telemt_me_reader_eof_total 278
telemt_me_idle_close_by_peer_total 278
telemt_me_route_drop_no_conn_total 90638
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279322
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 356
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
telemt_desync_total 1352
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 973
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 379
telemt_pool_swap_total 45
telemt_pool_force_close_total 1009
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 17878
telemt_me_writer_removed_unexpected_total 266
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1155
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17001
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1007
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16869
telemt_me_writer_teardown_success_total{mode="normal"} 18156
telemt_me_writer_teardown_noop_total 17878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36034
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.374965
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36034
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 278905
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 4703581560 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 159286131420 (148.35 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 123303.7 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8156475
telemt_connections_bad_total 836625
telemt_connections_current 3823
telemt_connections_me_current 3823
telemt_handshake_timeouts_total 230382
telemt_upstream_connect_attempt_total 48429
telemt_upstream_connect_success_total 48253
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 48390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1774
telemt_me_reconnect_success_total 955
telemt_me_reader_eof_total 938
telemt_me_idle_close_by_peer_total 938
telemt_me_route_drop_no_conn_total 2302930
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6089971
telemt_me_endpoint_quarantine_total 874
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 942
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
telemt_desync_total 24149
telemt_desync_full_logged_total 7946
telemt_desync_suppressed_total 16203
telemt_desync_frames_bucket_total{bucket="1_2"} 6002
telemt_desync_frames_bucket_total{bucket="3_10"} 8822
telemt_desync_frames_bucket_total{bucket="gt_10"} 9325
telemt_pool_swap_total 136
telemt_pool_force_close_total 3630
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 43729
telemt_me_writer_removed_unexpected_total 901
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3420
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41237
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3538
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40099
telemt_me_writer_teardown_success_total{mode="normal"} 44657
telemt_me_writer_teardown_noop_total 43731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88388
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.270698
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88388
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 850
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 6063971
telemt_user_connections_current{user="hello"} 3823
telemt_user_octets_from_client{user="hello"} 119235292116 (111.05 GB)
telemt_user_octets_to_client{user="hello"} 2842646608108 (2.59 TB)
telemt_user_unique_ips_current{user="hello"} 1542
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 123300.4 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7143614
telemt_connections_bad_total 739490
telemt_connections_current 3911
telemt_connections_me_current 3911
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 191024
telemt_upstream_connect_attempt_total 64169
telemt_upstream_connect_success_total 63680
telemt_upstream_connect_fail_total 426
telemt_upstream_connect_attempts_per_request{bucket="1"} 64106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 426
telemt_me_reconnect_attempts_total 5892
telemt_me_reconnect_success_total 1322
telemt_me_reader_eof_total 1186
telemt_me_idle_close_by_peer_total 1186
telemt_me_seq_mismatch_total 60
telemt_me_route_drop_no_conn_total 2363412
telemt_me_route_drop_channel_closed_total 197
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5450937
telemt_me_endpoint_quarantine_total 972
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 942
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
telemt_desync_total 23044
telemt_desync_full_logged_total 7651
telemt_desync_suppressed_total 15393
telemt_desync_frames_bucket_total{bucket="1_2"} 5725
telemt_desync_frames_bucket_total{bucket="3_10"} 8440
telemt_desync_frames_bucket_total{bucket="gt_10"} 8879
telemt_pool_swap_total 134
telemt_pool_force_close_total 3579
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 42164
telemt_me_writer_removed_unexpected_total 1200
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3971
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39454
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3352
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 227
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38585
telemt_me_writer_teardown_success_total{mode="normal"} 43425
telemt_me_writer_teardown_noop_total 42168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85593
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.274392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85593
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 263
telemt_me_writer_restored_same_endpoint_total 1027
telemt_me_writer_restored_fallback_total 79
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5452866
telemt_user_connections_current{user="hello"} 3911
telemt_user_octets_from_client{user="hello"} 101496978433 (94.53 GB)
telemt_user_octets_to_client{user="hello"} 2370595809124 (2.16 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1556
telemt_user_unique_ips_recent_window{user="hello"} 534
```