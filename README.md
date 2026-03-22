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

# Server Metrics 2026-03-22 18:53:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 78389.2 (21h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2901472
telemt_connections_bad_total 182324
telemt_connections_current 1368
telemt_connections_me_current 1368
telemt_handshake_timeouts_total 97164
telemt_upstream_connect_attempt_total 28664
telemt_upstream_connect_success_total 28663
telemt_upstream_connect_attempts_per_request{bucket="1"} 28663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1152
telemt_me_reconnect_success_total 485
telemt_me_reader_eof_total 488
telemt_me_idle_close_by_peer_total 488
telemt_me_route_drop_no_conn_total 2528797
telemt_me_route_drop_channel_closed_total 1018
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2461029
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 522
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 606
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_me_writers_warm_current 38
telemt_desync_total 10856
telemt_desync_full_logged_total 3448
telemt_desync_suppressed_total 7408
telemt_desync_frames_bucket_total{bucket="1_2"} 2915
telemt_desync_frames_bucket_total{bucket="3_10"} 4029
telemt_desync_frames_bucket_total{bucket="gt_10"} 3912
telemt_pool_swap_total 86
telemt_pool_force_close_total 2680
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 554
telemt_me_draining_writers_reap_progress_total 26165
telemt_me_writer_removed_unexpected_total 474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1906
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24475
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2627
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23485
telemt_me_writer_teardown_success_total{mode="normal"} 26381
telemt_me_writer_teardown_noop_total 26175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52556
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 283.369043
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52556
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 554
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2456739
telemt_user_connections_current{user="hello"} 1368
telemt_user_octets_from_client{user="hello"} 35422951616 (32.99 GB)
telemt_user_octets_to_client{user="hello"} 643509391940 (599.31 GB)
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 91756.2 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3771370
telemt_connections_bad_total 338402
telemt_connections_current 1153
telemt_connections_me_current 1153
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 96360
telemt_upstream_connect_attempt_total 55986
telemt_upstream_connect_success_total 55300
telemt_upstream_connect_fail_total 604
telemt_upstream_connect_attempts_per_request{bucket="1"} 55904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 604
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6381
telemt_me_reconnect_success_total 2339
telemt_me_reader_eof_total 2273
telemt_me_idle_close_by_peer_total 2273
telemt_me_route_drop_no_conn_total 3586094
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2996738
telemt_me_endpoint_quarantine_total 716
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 708
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 11922
telemt_desync_full_logged_total 6666
telemt_desync_suppressed_total 5256
telemt_desync_frames_bucket_total{bucket="1_2"} 2741
telemt_desync_frames_bucket_total{bucket="3_10"} 4666
telemt_desync_frames_bucket_total{bucket="gt_10"} 4515
telemt_pool_swap_total 86
telemt_pool_force_close_total 2600
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 221
telemt_me_draining_writers_reap_progress_total 36440
telemt_me_writer_removed_unexpected_total 2223
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4308
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34367
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33840
telemt_me_writer_teardown_success_total{mode="normal"} 38675
telemt_me_writer_teardown_noop_total 36440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75115
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.422823
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75115
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 221
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 2026
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 3007567
telemt_user_connections_current{user="hello"} 1153
telemt_user_octets_from_client{user="hello"} 38974086091 (36.30 GB)
telemt_user_octets_to_client{user="hello"} 701855222410 (653.65 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 678
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 166616.3 (46h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15780235
telemt_connections_bad_total 1520754
telemt_connections_current 2374
telemt_connections_me_current 2374
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 389868
telemt_upstream_connect_attempt_total 74391
telemt_upstream_connect_success_total 74294
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 74311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2762
telemt_me_reconnect_success_total 1417
telemt_me_reader_eof_total 1357
telemt_me_idle_close_by_peer_total 1355
telemt_me_route_drop_no_conn_total 13925567
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12572661
telemt_me_endpoint_quarantine_total 1055
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 51868
telemt_desync_full_logged_total 16300
telemt_desync_suppressed_total 35568
telemt_desync_frames_bucket_total{bucket="1_2"} 11582
telemt_desync_frames_bucket_total{bucket="3_10"} 20207
telemt_desync_frames_bucket_total{bucket="gt_10"} 20079
telemt_pool_swap_total 180
telemt_pool_force_close_total 6060
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 981
telemt_me_draining_writers_reap_progress_total 54667
telemt_me_writer_removed_unexpected_total 1310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4787
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50482
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5592
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48607
telemt_me_writer_teardown_success_total{mode="normal"} 55269
telemt_me_writer_teardown_noop_total 54717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109986
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 306.849115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109986
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 981
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1221
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12573321
telemt_user_connections_current{user="hello"} 2374
telemt_user_octets_from_client{user="hello"} 183069501957 (170.50 GB)
telemt_user_octets_to_client{user="hello"} 3302925669803 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 941
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 166617.4 (46h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11388735
telemt_connections_bad_total 1124509
telemt_connections_current 1515
telemt_connections_me_current 1515
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 339998
telemt_upstream_connect_attempt_total 86927
telemt_upstream_connect_success_total 85717
telemt_upstream_connect_fail_total 842
telemt_upstream_connect_attempts_per_request{bucket="1"} 86559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3706
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 842
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4099
telemt_me_reconnect_success_total 1694
telemt_me_reader_eof_total 1562
telemt_me_idle_close_by_peer_total 1562
telemt_me_route_drop_no_conn_total 4455837
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8486114
telemt_me_endpoint_quarantine_total 1056
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1259
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
telemt_me_writers_active_current 43
telemt_desync_total 37670
telemt_desync_full_logged_total 12692
telemt_desync_suppressed_total 24978
telemt_desync_frames_bucket_total{bucket="1_2"} 9283
telemt_desync_frames_bucket_total{bucket="3_10"} 14510
telemt_desync_frames_bucket_total{bucket="gt_10"} 13877
telemt_pool_swap_total 177
telemt_pool_force_close_total 5473
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 53170
telemt_me_writer_removed_unexpected_total 1601
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4904
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49711
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47697
telemt_me_writer_teardown_success_total{mode="normal"} 54615
telemt_me_writer_teardown_noop_total 53193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107808
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.069104
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107808
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 8424492
telemt_user_connections_current{user="hello"} 1515
telemt_user_octets_from_client{user="hello"} 210517639409 (196.06 GB)
telemt_user_octets_to_client{user="hello"} 3799138015350 (3.46 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 609
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 166580.7 (46h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10715466
telemt_connections_bad_total 923373
telemt_connections_current 1257
telemt_connections_me_current 1257
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342554
telemt_upstream_connect_attempt_total 71978
telemt_upstream_connect_success_total 70920
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 71104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4904
telemt_me_reconnect_success_total 1982
telemt_me_reader_eof_total 1731
telemt_me_idle_close_by_peer_total 1730
telemt_me_route_drop_no_conn_total 5226012
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8096277
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1223
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 27
telemt_desync_total 37180
telemt_desync_full_logged_total 12304
telemt_desync_suppressed_total 24876
telemt_desync_frames_bucket_total{bucket="1_2"} 9415
telemt_desync_frames_bucket_total{bucket="3_10"} 14232
telemt_desync_frames_bucket_total{bucket="gt_10"} 13533
telemt_pool_swap_total 174
telemt_pool_force_close_total 5405
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 53306
telemt_me_writer_removed_unexpected_total 1872
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5358
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49737
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4860
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47901
telemt_me_writer_teardown_success_total{mode="normal"} 55095
telemt_me_writer_teardown_noop_total 53377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.639240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1708
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 8088765
telemt_user_connections_current{user="hello"} 1257
telemt_user_octets_from_client{user="hello"} 186528258541 (173.72 GB)
telemt_user_octets_to_client{user="hello"} 3368063423929 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 36884.7 (10h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10630396
telemt_connections_bad_total 650691
telemt_connections_current 1540
telemt_connections_direct_current 333
telemt_connections_me_current 1207
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 221225
telemt_upstream_connect_attempt_total 43763
telemt_upstream_connect_success_total 41549
telemt_upstream_connect_fail_total 1507
telemt_upstream_connect_attempts_per_request{bucket="1"} 43056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5950
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1507
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6389
telemt_me_reconnect_success_total 845
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 25132848
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8827435
telemt_me_endpoint_quarantine_total 227
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 61
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 287
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
telemt_me_writers_active_current 22
telemt_desync_total 14171
telemt_desync_full_logged_total 3701
telemt_desync_suppressed_total 10470
telemt_desync_frames_bucket_total{bucket="1_2"} 2618
telemt_desync_frames_bucket_total{bucket="3_10"} 5735
telemt_desync_frames_bucket_total{bucket="gt_10"} 5818
telemt_pool_swap_total 36
telemt_pool_force_close_total 1345
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 412
telemt_me_draining_writers_reap_progress_total 10419
telemt_me_writer_removed_unexpected_total 773
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9551
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 289
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9074
telemt_me_writer_teardown_success_total{mode="normal"} 11151
telemt_me_writer_teardown_noop_total 10435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21586
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.274244
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21586
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 412
telemt_me_refill_failed_total 306
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 8849716
telemt_user_connections_current{user="hello"} 1540
telemt_user_octets_from_client{user="hello"} 80584954707 (75.05 GB)
telemt_user_octets_to_client{user="hello"} 432051342967 (402.38 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 166587.7 (46h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10567708
telemt_connections_bad_total 889996
telemt_connections_current 1694
telemt_connections_me_current 1694
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232939
telemt_upstream_connect_attempt_total 100960
telemt_upstream_connect_success_total 99895
telemt_upstream_connect_fail_total 907
telemt_upstream_connect_attempts_per_request{bucket="1"} 100802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1328
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 907
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72206
telemt_me_reconnect_success_total 2731
telemt_me_reader_eof_total 2423
telemt_me_idle_close_by_peer_total 2421
telemt_me_route_drop_no_conn_total 5156983
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8343585
telemt_me_endpoint_quarantine_total 1101
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 26
telemt_desync_total 44314
telemt_desync_full_logged_total 15100
telemt_desync_suppressed_total 29214
telemt_desync_frames_bucket_total{bucket="1_2"} 8994
telemt_desync_frames_bucket_total{bucket="3_10"} 17016
telemt_desync_frames_bucket_total{bucket="gt_10"} 18304
telemt_pool_swap_total 170
telemt_pool_force_close_total 5062
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 626
telemt_me_draining_writers_reap_progress_total 56711
telemt_me_writer_removed_unexpected_total 2463
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6030
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53168
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4365
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 697
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51649
telemt_me_writer_teardown_success_total{mode="normal"} 59198
telemt_me_writer_teardown_noop_total 56712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.859885
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 626
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2289
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8347090
telemt_user_connections_current{user="hello"} 1694
telemt_user_octets_from_client{user="hello"} 189611074585 (176.59 GB)
telemt_user_octets_to_client{user="hello"} 3166788017916 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 103423.8 (28h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11105811
telemt_connections_bad_total 430994
telemt_connections_current 1684
telemt_connections_me_current 1684
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4601890
telemt_upstream_connect_attempt_total 49160
telemt_upstream_connect_success_total 48795
telemt_upstream_connect_fail_total 356
telemt_upstream_connect_attempts_per_request{bucket="1"} 49151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 356
telemt_me_reconnect_attempts_total 48302
telemt_me_reconnect_success_total 1634
telemt_me_reader_eof_total 1293
telemt_me_idle_close_by_peer_total 1292
telemt_me_route_drop_no_conn_total 4003668
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5341189
telemt_me_endpoint_quarantine_total 663
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 778
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_writers_active_current 84
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29876
telemt_desync_full_logged_total 10106
telemt_desync_suppressed_total 19770
telemt_desync_frames_bucket_total{bucket="1_2"} 5990
telemt_desync_frames_bucket_total{bucket="3_10"} 11806
telemt_desync_frames_bucket_total{bucket="gt_10"} 12080
telemt_pool_swap_total 108
telemt_pool_force_close_total 3305
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 35702
telemt_me_writer_removed_unexpected_total 1354
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3206
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33883
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32397
telemt_me_writer_teardown_success_total{mode="normal"} 37089
telemt_me_writer_teardown_noop_total 35709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72798
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.318300
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72798
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1458
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5334254
telemt_user_connections_current{user="hello"} 1684
telemt_user_octets_from_client{user="hello"} 114697503060 (106.82 GB)
telemt_user_octets_to_client{user="hello"} 2034697769322 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 690
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 84394.5 (23h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1240562
telemt_connections_bad_total 27137
telemt_connections_current 1103
telemt_connections_me_current 1103
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 23955
telemt_upstream_connect_attempt_total 40382
telemt_upstream_connect_success_total 40261
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 40355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 662
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1791
telemt_me_reconnect_success_total 776
telemt_me_reader_eof_total 748
telemt_me_idle_close_by_peer_total 748
telemt_me_route_drop_no_conn_total 432987
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1098898
telemt_me_endpoint_quarantine_total 707
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 694
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
telemt_desync_total 6386
telemt_desync_full_logged_total 1970
telemt_desync_suppressed_total 4416
telemt_desync_frames_bucket_total{bucket="1_2"} 1453
telemt_desync_frames_bucket_total{bucket="3_10"} 2514
telemt_desync_frames_bucket_total{bucket="gt_10"} 2419
telemt_pool_swap_total 90
telemt_pool_force_close_total 2321
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 33571
telemt_me_writer_removed_unexpected_total 722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2627
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31695
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2236
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31250
telemt_me_writer_teardown_success_total{mode="normal"} 34322
telemt_me_writer_teardown_noop_total 33575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67897
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.078609
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67897
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 658
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1095151
telemt_user_connections_current{user="hello"} 1103
telemt_user_octets_from_client{user="hello"} 20462918565 (19.06 GB)
telemt_user_octets_to_client{user="hello"} 465766513955 (433.78 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 166592.5 (46h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12880456
telemt_connections_bad_total 1503615
telemt_connections_current 1865
telemt_connections_me_current 1865
telemt_handshake_timeouts_total 365044
telemt_upstream_connect_attempt_total 62730
telemt_upstream_connect_success_total 62401
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 62595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2435
telemt_me_reconnect_success_total 1296
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 4383899
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9743412
telemt_me_endpoint_quarantine_total 1109
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1242
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 38
telemt_desync_total 40072
telemt_desync_full_logged_total 13067
telemt_desync_suppressed_total 27005
telemt_desync_frames_bucket_total{bucket="1_2"} 9565
telemt_desync_frames_bucket_total{bucket="3_10"} 14794
telemt_desync_frames_bucket_total{bucket="gt_10"} 15713
telemt_pool_swap_total 184
telemt_pool_force_close_total 5073
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 642
telemt_me_draining_writers_reap_progress_total 56436
telemt_me_writer_removed_unexpected_total 1211
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4635
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53048
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4899
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51363
telemt_me_writer_teardown_success_total{mode="normal"} 57683
telemt_me_writer_teardown_noop_total 56438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114121
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.100770
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114121
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 642
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9711346
telemt_user_connections_current{user="hello"} 1865
telemt_user_octets_from_client{user="hello"} 190069410416 (177.02 GB)
telemt_user_octets_to_client{user="hello"} 4282816233104 (3.90 TB)
telemt_user_unique_ips_current{user="hello"} 649
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 166589.1 (46h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11181726
telemt_connections_bad_total 1261028
telemt_connections_current 1644
telemt_connections_me_current 1644
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 293141
telemt_upstream_connect_attempt_total 89071
telemt_upstream_connect_success_total 88259
telemt_upstream_connect_fail_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 88865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 606
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9594
telemt_me_reconnect_success_total 2302
telemt_me_reader_eof_total 2147
telemt_me_idle_close_by_peer_total 2146
telemt_me_seq_mismatch_total 77
telemt_me_route_drop_no_conn_total 5561242
telemt_me_route_drop_channel_closed_total 352
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8645746
telemt_me_endpoint_quarantine_total 1272
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1242
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
telemt_me_writers_active_current 83
telemt_me_writers_warm_current 30
telemt_desync_total 39421
telemt_desync_full_logged_total 12738
telemt_desync_suppressed_total 26683
telemt_desync_frames_bucket_total{bucket="1_2"} 9819
telemt_desync_frames_bucket_total{bucket="3_10"} 14665
telemt_desync_frames_bucket_total{bucket="gt_10"} 14937
telemt_pool_swap_total 174
telemt_pool_force_close_total 4863
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 629
telemt_me_draining_writers_reap_progress_total 56136
telemt_me_writer_removed_unexpected_total 2180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5944
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52445
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51273
telemt_me_writer_teardown_success_total{mode="normal"} 58389
telemt_me_writer_teardown_noop_total 56141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.044588
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 629
telemt_me_refill_failed_total 376
telemt_me_writer_restored_same_endpoint_total 1880
telemt_me_writer_restored_fallback_total 105
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 8651488
telemt_user_connections_current{user="hello"} 1644
telemt_user_octets_from_client{user="hello"} 152219335893 (141.77 GB)
telemt_user_octets_to_client{user="hello"} 3326441516175 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 221
```