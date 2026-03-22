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

# Server Metrics 2026-03-22 13:51:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 60283.5 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1895506
telemt_connections_bad_total 82802
telemt_connections_current 1855
telemt_connections_me_current 1855
telemt_handshake_timeouts_total 79787
telemt_upstream_connect_attempt_total 22544
telemt_upstream_connect_success_total 22543
telemt_upstream_connect_attempts_per_request{bucket="1"} 22543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 367
telemt_me_reader_eof_total 371
telemt_me_idle_close_by_peer_total 371
telemt_me_route_drop_no_conn_total 1320466
telemt_me_route_drop_channel_closed_total 605
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1612345
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 412
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 474
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
telemt_me_writers_active_current 43
telemt_desync_total 8828
telemt_desync_full_logged_total 2704
telemt_desync_suppressed_total 6124
telemt_desync_frames_bucket_total{bucket="1_2"} 2460
telemt_desync_frames_bucket_total{bucket="3_10"} 3310
telemt_desync_frames_bucket_total{bucket="gt_10"} 3058
telemt_pool_swap_total 66
telemt_pool_force_close_total 1977
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 322
telemt_me_draining_writers_reap_progress_total 20556
telemt_me_writer_removed_unexpected_total 362
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1464
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19313
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18579
telemt_me_writer_teardown_success_total{mode="normal"} 20777
telemt_me_writer_teardown_noop_total 20560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41337
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.446531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41337
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 322
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 326
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1609413
telemt_user_connections_current{user="hello"} 1855
telemt_user_octets_from_client{user="hello"} 25363030396 (23.62 GB)
telemt_user_octets_to_client{user="hello"} 471404178060 (439.03 GB)
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 73649.9 (20h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3069730
telemt_connections_bad_total 286017
telemt_connections_current 2281
telemt_connections_me_current 2281
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 72742
telemt_upstream_connect_attempt_total 47201
telemt_upstream_connect_success_total 46640
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 47136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3694
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1546
telemt_me_route_drop_no_conn_total 2870984
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2416237
telemt_me_endpoint_quarantine_total 612
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 575
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
telemt_me_writers_active_current 83
telemt_desync_total 9558
telemt_desync_full_logged_total 5333
telemt_desync_suppressed_total 4225
telemt_desync_frames_bucket_total{bucket="1_2"} 2247
telemt_desync_frames_bucket_total{bucket="3_10"} 3755
telemt_desync_frames_bucket_total{bucket="gt_10"} 3556
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 29016
telemt_me_writer_removed_unexpected_total 1503
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3193
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27327
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26946
telemt_me_writer_teardown_success_total{mode="normal"} 30520
telemt_me_writer_teardown_noop_total 29016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59536
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.777691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59536
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1393
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 2427809
telemt_user_connections_current{user="hello"} 2281
telemt_user_octets_from_client{user="hello"} 29289298467 (27.28 GB)
telemt_user_octets_to_client{user="hello"} 556251135534 (518.05 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1385
telemt_user_unique_ips_recent_window{user="hello"} 567
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 148509.7 (41h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13933801
telemt_connections_bad_total 1225635
telemt_connections_current 5046
telemt_connections_me_current 5046
telemt_handshake_timeouts_total 351062
telemt_upstream_connect_attempt_total 53859
telemt_upstream_connect_success_total 53777
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29186
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2457
telemt_me_reconnect_success_total 1281
telemt_me_reader_eof_total 1224
telemt_me_idle_close_by_peer_total 1223
telemt_me_route_drop_no_conn_total 12118841
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11175872
telemt_me_endpoint_quarantine_total 943
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1105
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
telemt_desync_total 45490
telemt_desync_full_logged_total 14436
telemt_desync_suppressed_total 31054
telemt_desync_frames_bucket_total{bucket="1_2"} 10315
telemt_desync_frames_bucket_total{bucket="3_10"} 17792
telemt_desync_frames_bucket_total{bucket="gt_10"} 17383
telemt_pool_swap_total 159
telemt_pool_force_close_total 5440
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 862
telemt_me_draining_writers_reap_progress_total 49113
telemt_me_writer_removed_unexpected_total 1180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4259
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5008
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 432
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43673
telemt_me_writer_teardown_success_total{mode="normal"} 49628
telemt_me_writer_teardown_noop_total 49162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98790
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 252.562691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98790
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 862
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 11163776
telemt_user_connections_current{user="hello"} 5046
telemt_user_octets_from_client{user="hello"} 160564373764 (149.54 GB)
telemt_user_octets_to_client{user="hello"} 2977783616192 (2.71 TB)
telemt_user_unique_ips_current{user="hello"} 2048
telemt_user_unique_ips_recent_window{user="hello"} 705
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 148511.1 (41h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10347682
telemt_connections_bad_total 981903
telemt_connections_current 4480
telemt_connections_me_current 4480
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 309470
telemt_upstream_connect_attempt_total 80204
telemt_upstream_connect_success_total 79064
telemt_upstream_connect_fail_total 819
telemt_upstream_connect_attempts_per_request{bucket="1"} 79883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 819
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3692
telemt_me_reconnect_success_total 1465
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 4114239
telemt_me_route_drop_channel_closed_total 446
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7719965
telemt_me_endpoint_quarantine_total 928
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1124
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 34516
telemt_desync_full_logged_total 11608
telemt_desync_suppressed_total 22908
telemt_desync_frames_bucket_total{bucket="1_2"} 8518
telemt_desync_frames_bucket_total{bucket="3_10"} 13268
telemt_desync_frames_bucket_total{bucket="gt_10"} 12730
telemt_pool_swap_total 158
telemt_pool_force_close_total 4877
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 612
telemt_me_draining_writers_reap_progress_total 47301
telemt_me_writer_removed_unexpected_total 1372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4290
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44239
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4455
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 422
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42424
telemt_me_writer_teardown_success_total{mode="normal"} 48529
telemt_me_writer_teardown_noop_total 47316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95845
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 90.211240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95845
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 612
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1242
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 7659531
telemt_user_connections_current{user="hello"} 4480
telemt_user_octets_from_client{user="hello"} 194742904953 (181.37 GB)
telemt_user_octets_to_client{user="hello"} 3456833913706 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1846
telemt_user_unique_ips_recent_window{user="hello"} 653
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 148475.1 (41h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9798409
telemt_connections_bad_total 823092
telemt_connections_current 4126
telemt_connections_me_current 4126
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 316428
telemt_upstream_connect_attempt_total 65664
telemt_upstream_connect_success_total 64761
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 64942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4175
telemt_me_reconnect_success_total 1802
telemt_me_reader_eof_total 1569
telemt_me_idle_close_by_peer_total 1568
telemt_me_route_drop_no_conn_total 4842561
telemt_me_route_drop_channel_closed_total 329
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7397492
telemt_me_endpoint_quarantine_total 1018
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1088
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 34258
telemt_desync_full_logged_total 11374
telemt_desync_suppressed_total 22884
telemt_desync_frames_bucket_total{bucket="1_2"} 8671
telemt_desync_frames_bucket_total{bucket="3_10"} 13132
telemt_desync_frames_bucket_total{bucket="gt_10"} 12455
telemt_pool_swap_total 154
telemt_pool_force_close_total 4809
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 47949
telemt_me_writer_removed_unexpected_total 1714
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4794
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44793
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43140
telemt_me_writer_teardown_success_total{mode="normal"} 49587
telemt_me_writer_teardown_noop_total 48016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3153.756927
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 122
telemt_me_writer_restored_same_endpoint_total 1572
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 7391489
telemt_user_connections_current{user="hello"} 4126
telemt_user_octets_from_client{user="hello"} 173453960353 (161.54 GB)
telemt_user_octets_to_client{user="hello"} 3085917378489 (2.81 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1792
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 18755.2 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7908183
telemt_connections_bad_total 503515
telemt_connections_current 7576
telemt_connections_me_current 7576
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 126631
telemt_upstream_connect_attempt_total 28175
telemt_upstream_connect_success_total 26803
telemt_upstream_connect_fail_total 1018
telemt_upstream_connect_attempts_per_request{bucket="1"} 27821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4719
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1018
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 2691
telemt_me_reconnect_success_total 513
telemt_me_reader_eof_total 317
telemt_me_idle_close_by_peer_total 317
telemt_me_route_drop_no_conn_total 19356924
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6579171
telemt_me_endpoint_quarantine_total 115
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 61
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 61
telemt_me_single_endpoint_shadow_rotate_total 146
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
telemt_me_writers_active_current 58
telemt_desync_total 9613
telemt_desync_full_logged_total 2463
telemt_desync_suppressed_total 7150
telemt_desync_frames_bucket_total{bucket="1_2"} 1705
telemt_desync_frames_bucket_total{bucket="3_10"} 3895
telemt_desync_frames_bucket_total{bucket="gt_10"} 4013
telemt_pool_swap_total 17
telemt_pool_force_close_total 697
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 4880
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 849
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4437
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4183
telemt_me_writer_teardown_success_total{mode="normal"} 5286
telemt_me_writer_teardown_noop_total 4883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10169
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.863376
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10169
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 114
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 2805
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6594194
telemt_user_connections_current{user="hello"} 7576
telemt_user_octets_from_client{user="hello"} 37067662639 (34.52 GB)
telemt_user_octets_to_client{user="hello"} 193859737712 (180.55 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2523
telemt_user_unique_ips_recent_window{user="hello"} 1453
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 148481.9 (41h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9512079
telemt_connections_bad_total 789189
telemt_connections_current 5032
telemt_connections_me_current 5032
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 205827
telemt_upstream_connect_attempt_total 89954
telemt_upstream_connect_success_total 89050
telemt_upstream_connect_fail_total 782
telemt_upstream_connect_attempts_per_request{bucket="1"} 89832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 782
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71351
telemt_me_reconnect_success_total 2422
telemt_me_reader_eof_total 2152
telemt_me_idle_close_by_peer_total 2151
telemt_me_route_drop_no_conn_total 4624785
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7506416
telemt_me_endpoint_quarantine_total 996
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1107
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38431
telemt_desync_full_logged_total 13127
telemt_desync_suppressed_total 25304
telemt_desync_frames_bucket_total{bucket="1_2"} 7808
telemt_desync_frames_bucket_total{bucket="3_10"} 14871
telemt_desync_frames_bucket_total{bucket="gt_10"} 15752
telemt_pool_swap_total 152
telemt_pool_force_close_total 4500
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 548
telemt_me_draining_writers_reap_progress_total 50583
telemt_me_writer_removed_unexpected_total 2179
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5341
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47438
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3885
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 615
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46083
telemt_me_writer_teardown_success_total{mode="normal"} 52779
telemt_me_writer_teardown_noop_total 50584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103363
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.716612
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103363
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 548
telemt_me_refill_failed_total 4253
telemt_me_writer_restored_same_endpoint_total 2030
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 7507641
telemt_user_connections_current{user="hello"} 5032
telemt_user_octets_from_client{user="hello"} 173213363947 (161.32 GB)
telemt_user_octets_to_client{user="hello"} 2857575583277 (2.60 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2032
telemt_user_unique_ips_recent_window{user="hello"} 665
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 85318.0 (23h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9491073
telemt_connections_bad_total 340001
telemt_connections_current 4430
telemt_connections_me_current 4430
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3993428
telemt_upstream_connect_attempt_total 42211
telemt_upstream_connect_success_total 41906
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 42204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_reconnect_attempts_total 47924
telemt_me_reconnect_success_total 1439
telemt_me_reader_eof_total 1107
telemt_me_idle_close_by_peer_total 1107
telemt_me_route_drop_no_conn_total 3468757
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4573158
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 641
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 25023
telemt_desync_full_logged_total 8389
telemt_desync_suppressed_total 16634
telemt_desync_frames_bucket_total{bucket="1_2"} 5054
telemt_desync_frames_bucket_total{bucket="3_10"} 9888
telemt_desync_frames_bucket_total{bucket="gt_10"} 10081
telemt_pool_swap_total 89
telemt_pool_force_close_total 2769
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 287
telemt_me_draining_writers_reap_progress_total 29595
telemt_me_writer_removed_unexpected_total 1172
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2676
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28119
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26826
telemt_me_writer_teardown_success_total{mode="normal"} 30795
telemt_me_writer_teardown_noop_total 29602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60397
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.138818
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60397
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 287
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1286
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4567733
telemt_user_connections_current{user="hello"} 4430
telemt_user_octets_from_client{user="hello"} 100226890912 (93.34 GB)
telemt_user_octets_to_client{user="hello"} 1747685577294 (1.59 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1798
telemt_user_unique_ips_recent_window{user="hello"} 682
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 66288.9 (18h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788034
telemt_connections_bad_total 10476
telemt_connections_current 1117
telemt_connections_me_current 1117
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14927
telemt_upstream_connect_attempt_total 33574
telemt_upstream_connect_success_total 33490
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1517
telemt_me_reconnect_success_total 653
telemt_me_reader_eof_total 629
telemt_me_idle_close_by_peer_total 629
telemt_me_route_drop_no_conn_total 265295
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706081
telemt_me_endpoint_quarantine_total 597
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 554
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 3909
telemt_desync_full_logged_total 1175
telemt_desync_suppressed_total 2734
telemt_desync_frames_bucket_total{bucket="1_2"} 954
telemt_desync_frames_bucket_total{bucket="3_10"} 1562
telemt_desync_frames_bucket_total{bucket="gt_10"} 1393
telemt_pool_swap_total 70
telemt_pool_force_close_total 1738
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 27579
telemt_me_writer_removed_unexpected_total 608
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2120
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1660
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25841
telemt_me_writer_teardown_success_total{mode="normal"} 28210
telemt_me_writer_teardown_noop_total 27581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55791
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.035586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55791
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 559
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 707516
telemt_user_connections_current{user="hello"} 1117
telemt_user_octets_from_client{user="hello"} 13275927261 (12.36 GB)
telemt_user_octets_to_client{user="hello"} 333511676899 (310.61 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 148486.3 (41h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11601862
telemt_connections_bad_total 1354862
telemt_connections_current 5777
telemt_connections_me_current 5777
telemt_handshake_timeouts_total 316030
telemt_upstream_connect_attempt_total 55938
telemt_upstream_connect_success_total 55722
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 55890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_reconnect_attempts_total 2191
telemt_me_reconnect_success_total 1167
telemt_me_reader_eof_total 1132
telemt_me_idle_close_by_peer_total 1132
telemt_me_route_drop_no_conn_total 3670497
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8723390
telemt_me_endpoint_quarantine_total 1016
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1112
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 35862
telemt_desync_full_logged_total 11745
telemt_desync_suppressed_total 24117
telemt_desync_frames_bucket_total{bucket="1_2"} 8541
telemt_desync_frames_bucket_total{bucket="3_10"} 13286
telemt_desync_frames_bucket_total{bucket="gt_10"} 14035
telemt_pool_swap_total 164
telemt_pool_force_close_total 4516
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 565
telemt_me_draining_writers_reap_progress_total 50397
telemt_me_writer_removed_unexpected_total 1087
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4126
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47388
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45881
telemt_me_writer_teardown_success_total{mode="normal"} 51514
telemt_me_writer_teardown_noop_total 50399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101913
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.451304
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101913
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 565
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1023
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8693876
telemt_user_connections_current{user="hello"} 5777
telemt_user_octets_from_client{user="hello"} 167955947000 (156.42 GB)
telemt_user_octets_to_client{user="hello"} 3917421753804 (3.56 TB)
telemt_user_unique_ips_current{user="hello"} 2184
telemt_user_unique_ips_recent_window{user="hello"} 809
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 148483.1 (41h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10024938
telemt_connections_bad_total 1123844
telemt_connections_current 5118
telemt_connections_me_current 5118
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 262634
telemt_upstream_connect_attempt_total 81549
telemt_upstream_connect_success_total 80952
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 81468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_reconnect_attempts_total 8574
telemt_me_reconnect_success_total 1939
telemt_me_reader_eof_total 1808
telemt_me_idle_close_by_peer_total 1808
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4539733
telemt_me_route_drop_channel_closed_total 318
telemt_me_route_drop_queue_full_total 17
telemt_me_route_drop_queue_full_profile_total{profile="high"} 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7718602
telemt_me_endpoint_quarantine_total 1134
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1112
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
telemt_me_writers_active_current 47
telemt_desync_total 35072
telemt_desync_full_logged_total 11421
telemt_desync_suppressed_total 23651
telemt_desync_frames_bucket_total{bucket="1_2"} 8650
telemt_desync_frames_bucket_total{bucket="3_10"} 13059
telemt_desync_frames_bucket_total{bucket="gt_10"} 13363
telemt_pool_swap_total 157
telemt_pool_force_close_total 4374
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 563
telemt_me_draining_writers_reap_progress_total 49738
telemt_me_writer_removed_unexpected_total 1833
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5149
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46489
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3976
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45364
telemt_me_writer_teardown_success_total{mode="normal"} 51638
telemt_me_writer_teardown_noop_total 49742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101380
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.278295
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101380
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 563
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1577
telemt_me_writer_restored_fallback_total 96
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 7725609
telemt_user_connections_current{user="hello"} 5118
telemt_user_octets_from_client{user="hello"} 136137000937 (126.79 GB)
telemt_user_octets_to_client{user="hello"} 3037771439743 (2.76 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2013
telemt_user_unique_ips_recent_window{user="hello"} 810
```