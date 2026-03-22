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

# Server Metrics 2026-03-22 14:26:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 62435.0 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2009351
telemt_connections_bad_total 86596
telemt_connections_current 1647
telemt_connections_me_current 1647
telemt_handshake_timeouts_total 82382
telemt_upstream_connect_attempt_total 23319
telemt_upstream_connect_success_total 23318
telemt_upstream_connect_attempts_per_request{bucket="1"} 23318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 949
telemt_me_reconnect_success_total 384
telemt_me_reader_eof_total 389
telemt_me_idle_close_by_peer_total 389
telemt_me_route_drop_no_conn_total 1461865
telemt_me_route_drop_channel_closed_total 653
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1713419
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 492
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
telemt_desync_total 9160
telemt_desync_full_logged_total 2830
telemt_desync_suppressed_total 6330
telemt_desync_frames_bucket_total{bucket="1_2"} 2525
telemt_desync_frames_bucket_total{bucket="3_10"} 3431
telemt_desync_frames_bucket_total{bucket="gt_10"} 3204
telemt_pool_swap_total 69
telemt_pool_force_close_total 2109
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 21280
telemt_me_writer_removed_unexpected_total 379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1524
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19955
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2068
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19171
telemt_me_writer_teardown_success_total{mode="normal"} 21479
telemt_me_writer_teardown_noop_total 21284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 169.282060
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1710391
telemt_user_connections_current{user="hello"} 1647
telemt_user_octets_from_client{user="hello"} 26720886996 (24.89 GB)
telemt_user_octets_to_client{user="hello"} 495197112572 (461.19 GB)
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 75801.4 (21h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3232121
telemt_connections_bad_total 295345
telemt_connections_current 1601
telemt_connections_me_current 1601
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 77230
telemt_upstream_connect_attempt_total 48657
telemt_upstream_connect_success_total 48071
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 48590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5577
telemt_me_reconnect_success_total 1887
telemt_me_reader_eof_total 1813
telemt_me_idle_close_by_peer_total 1813
telemt_me_route_drop_no_conn_total 3030958
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2552249
telemt_me_endpoint_quarantine_total 624
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 589
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
telemt_me_writers_active_current 43
telemt_desync_total 10067
telemt_desync_full_logged_total 5607
telemt_desync_suppressed_total 4460
telemt_desync_frames_bucket_total{bucket="1_2"} 2379
telemt_desync_frames_bucket_total{bucket="3_10"} 3960
telemt_desync_frames_bucket_total{bucket="gt_10"} 3728
telemt_pool_swap_total 73
telemt_pool_force_close_total 2116
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 30133
telemt_me_writer_removed_unexpected_total 1771
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3508
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28397
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28017
telemt_me_writer_teardown_success_total{mode="normal"} 31905
telemt_me_writer_teardown_noop_total 30133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62038
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.063302
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62038
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1601
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 2563703
telemt_user_connections_current{user="hello"} 1601
telemt_user_octets_from_client{user="hello"} 30917031587 (28.79 GB)
telemt_user_octets_to_client{user="hello"} 587615885334 (547.26 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 786
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 150661.3 (41h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14390682
telemt_connections_bad_total 1271897
telemt_connections_current 5325
telemt_connections_me_current 5325
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 358951
telemt_upstream_connect_attempt_total 68888
telemt_upstream_connect_success_total 68797
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 68814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1648
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2523
telemt_me_reconnect_success_total 1307
telemt_me_reader_eof_total 1246
telemt_me_idle_close_by_peer_total 1245
telemt_me_route_drop_no_conn_total 12700515
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11531278
telemt_me_endpoint_quarantine_total 959
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1122
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
telemt_me_writers_active_current 43
telemt_desync_total 46923
telemt_desync_full_logged_total 14814
telemt_desync_suppressed_total 32109
telemt_desync_frames_bucket_total{bucket="1_2"} 10621
telemt_desync_frames_bucket_total{bucket="3_10"} 18358
telemt_desync_frames_bucket_total{bucket="gt_10"} 17944
telemt_pool_swap_total 162
telemt_pool_force_close_total 5511
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 897
telemt_me_draining_writers_reap_progress_total 49731
telemt_me_writer_removed_unexpected_total 1201
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4329
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45923
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44220
telemt_me_writer_teardown_success_total{mode="normal"} 50252
telemt_me_writer_teardown_noop_total 49780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.411771
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 897
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1121
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 11533088
telemt_user_connections_current{user="hello"} 5325
telemt_user_octets_from_client{user="hello"} 163882405309 (152.63 GB)
telemt_user_octets_to_client{user="hello"} 3034565823007 (2.76 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 2012
telemt_user_unique_ips_recent_window{user="hello"} 799
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 150662.5 (41h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10588573
telemt_connections_bad_total 1011216
telemt_connections_current 4401
telemt_connections_me_current 4401
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 315233
telemt_upstream_connect_attempt_total 80913
telemt_upstream_connect_success_total 79769
telemt_upstream_connect_fail_total 822
telemt_upstream_connect_attempts_per_request{bucket="1"} 80591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 822
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3710
telemt_me_reconnect_success_total 1481
telemt_me_reader_eof_total 1356
telemt_me_idle_close_by_peer_total 1356
telemt_me_route_drop_no_conn_total 4205401
telemt_me_route_drop_channel_closed_total 460
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7907120
telemt_me_endpoint_quarantine_total 944
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1144
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
telemt_me_writers_active_current 47
telemt_desync_total 35216
telemt_desync_full_logged_total 11855
telemt_desync_suppressed_total 23361
telemt_desync_frames_bucket_total{bucket="1_2"} 8672
telemt_desync_frames_bucket_total{bucket="3_10"} 13552
telemt_desync_frames_bucket_total{bucket="gt_10"} 12992
telemt_pool_swap_total 161
telemt_pool_force_close_total 4976
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 623
telemt_me_draining_writers_reap_progress_total 47935
telemt_me_writer_removed_unexpected_total 1388
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4367
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44813
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4545
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 431
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42959
telemt_me_writer_teardown_success_total{mode="normal"} 49180
telemt_me_writer_teardown_noop_total 47950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97130
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 95.251539
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97130
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 623
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1257
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 7846318
telemt_user_connections_current{user="hello"} 4401
telemt_user_octets_from_client{user="hello"} 198178521377 (184.57 GB)
telemt_user_octets_to_client{user="hello"} 3536390067574 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1762
telemt_user_unique_ips_recent_window{user="hello"} 579
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 150627.3 (41h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10034107
telemt_connections_bad_total 851253
telemt_connections_current 4029
telemt_connections_me_current 4029
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 323109
telemt_upstream_connect_attempt_total 66329
telemt_upstream_connect_success_total 65416
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 65598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2022
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4532
telemt_me_reconnect_success_total 1841
telemt_me_reader_eof_total 1594
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 4931433
telemt_me_route_drop_channel_closed_total 338
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7577912
telemt_me_endpoint_quarantine_total 1040
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1104
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 35049
telemt_desync_full_logged_total 11614
telemt_desync_suppressed_total 23435
telemt_desync_frames_bucket_total{bucket="1_2"} 8880
telemt_desync_frames_bucket_total{bucket="3_10"} 13407
telemt_desync_frames_bucket_total{bucket="gt_10"} 12762
telemt_pool_swap_total 157
telemt_pool_force_close_total 4928
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 48551
telemt_me_writer_removed_unexpected_total 1738
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4869
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45329
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4399
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 529
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43623
telemt_me_writer_teardown_success_total{mode="normal"} 50198
telemt_me_writer_teardown_noop_total 48621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98819
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3165.405987
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98819
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1598
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7571419
telemt_user_connections_current{user="hello"} 4029
telemt_user_octets_from_client{user="hello"} 176967736729 (164.81 GB)
telemt_user_octets_to_client{user="hello"} 3157081604025 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1685
telemt_user_unique_ips_recent_window{user="hello"} 564
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 20906.2 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8839350
telemt_connections_bad_total 559541
telemt_connections_current 6581
telemt_connections_me_current 6581
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 142110
telemt_upstream_connect_attempt_total 29100
telemt_upstream_connect_success_total 27662
telemt_upstream_connect_fail_total 1033
telemt_upstream_connect_attempts_per_request{bucket="1"} 28695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4749
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1033
telemt_me_keepalive_timeout_total 846
telemt_me_reconnect_attempts_total 5519
telemt_me_reconnect_success_total 596
telemt_me_reader_eof_total 391
telemt_me_idle_close_by_peer_total 391
telemt_me_route_drop_no_conn_total 21650945
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7350304
telemt_me_endpoint_quarantine_total 133
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 160
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
telemt_me_writers_active_current 44
telemt_desync_total 10888
telemt_desync_full_logged_total 2805
telemt_desync_suppressed_total 8083
telemt_desync_frames_bucket_total{bucket="1_2"} 1915
telemt_desync_frames_bucket_total{bucket="3_10"} 4384
telemt_desync_frames_bucket_total{bucket="gt_10"} 4589
telemt_pool_swap_total 19
telemt_pool_force_close_total 821
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 293
telemt_me_draining_writers_reap_progress_total 5613
telemt_me_writer_removed_unexpected_total 510
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5099
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 560
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 261
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4792
telemt_me_writer_teardown_success_total{mode="normal"} 6086
telemt_me_writer_teardown_noop_total 5617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11703
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.959657
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11703
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 293
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 426
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 7365049
telemt_user_connections_current{user="hello"} 6581
telemt_user_octets_from_client{user="hello"} 42604285719 (39.68 GB)
telemt_user_octets_to_client{user="hello"} 216369163212 (201.51 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2410
telemt_user_unique_ips_recent_window{user="hello"} 1501
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 150633.3 (41h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9771929
telemt_connections_bad_total 813703
telemt_connections_current 4187
telemt_connections_me_current 4187
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 212127
telemt_upstream_connect_attempt_total 90838
telemt_upstream_connect_success_total 89920
telemt_upstream_connect_fail_total 796
telemt_upstream_connect_attempts_per_request{bucket="1"} 90716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 796
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71445
telemt_me_reconnect_success_total 2476
telemt_me_reader_eof_total 2207
telemt_me_idle_close_by_peer_total 2206
telemt_me_route_drop_no_conn_total 4819397
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7710015
telemt_me_endpoint_quarantine_total 1014
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1124
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
telemt_me_writers_active_current 43
telemt_desync_total 39666
telemt_desync_full_logged_total 13577
telemt_desync_suppressed_total 26089
telemt_desync_frames_bucket_total{bucket="1_2"} 8066
telemt_desync_frames_bucket_total{bucket="3_10"} 15391
telemt_desync_frames_bucket_total{bucket="gt_10"} 16209
telemt_pool_swap_total 154
telemt_pool_force_close_total 4592
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 559
telemt_me_draining_writers_reap_progress_total 51360
telemt_me_writer_removed_unexpected_total 2233
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5440
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48171
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 650
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46768
telemt_me_writer_teardown_success_total{mode="normal"} 53611
telemt_me_writer_teardown_noop_total 51361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104972
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.971516
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104972
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 559
telemt_me_refill_failed_total 4255
telemt_me_writer_restored_same_endpoint_total 2081
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 7710817
telemt_user_connections_current{user="hello"} 4187
telemt_user_octets_from_client{user="hello"} 176560135987 (164.43 GB)
telemt_user_octets_to_client{user="hello"} 2914076461653 (2.65 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1644
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 87469.4 (24h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9934556
telemt_connections_bad_total 360385
telemt_connections_current 5315
telemt_connections_me_current 5315
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4184039
telemt_upstream_connect_attempt_total 42895
telemt_upstream_connect_success_total 42585
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 42888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 47938
telemt_me_reconnect_success_total 1451
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_route_drop_no_conn_total 3717150
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4780175
telemt_me_endpoint_quarantine_total 574
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 657
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
telemt_desync_total 26095
telemt_desync_full_logged_total 8783
telemt_desync_suppressed_total 17312
telemt_desync_frames_bucket_total{bucket="1_2"} 5280
telemt_desync_frames_bucket_total{bucket="3_10"} 10341
telemt_desync_frames_bucket_total{bucket="gt_10"} 10474
telemt_pool_swap_total 92
telemt_pool_force_close_total 2833
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 292
telemt_me_draining_writers_reap_progress_total 30176
telemt_me_writer_removed_unexpected_total 1186
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2732
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28658
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2421
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27343
telemt_me_writer_teardown_success_total{mode="normal"} 31390
telemt_me_writer_teardown_noop_total 30183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61573
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.214607
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61573
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 292
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1298
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4774429
telemt_user_connections_current{user="hello"} 5315
telemt_user_octets_from_client{user="hello"} 103832447352 (96.70 GB)
telemt_user_octets_to_client{user="hello"} 1804049049402 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2172
telemt_user_unique_ips_recent_window{user="hello"} 653
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 68440.2 (19h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 836824
telemt_connections_bad_total 10750
telemt_connections_current 1037
telemt_connections_me_current 1037
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15775
telemt_upstream_connect_attempt_total 34421
telemt_upstream_connect_success_total 34336
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 34405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 459
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1564
telemt_me_reconnect_success_total 667
telemt_me_reader_eof_total 642
telemt_me_idle_close_by_peer_total 642
telemt_me_route_drop_no_conn_total 287835
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 746310
telemt_me_endpoint_quarantine_total 610
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 567
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
telemt_me_writers_warm_current 10
telemt_desync_total 4109
telemt_desync_full_logged_total 1246
telemt_desync_suppressed_total 2863
telemt_desync_frames_bucket_total{bucket="1_2"} 992
telemt_desync_frames_bucket_total{bucket="3_10"} 1637
telemt_desync_frames_bucket_total{bucket="gt_10"} 1480
telemt_pool_swap_total 72
telemt_pool_force_close_total 1798
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 28299
telemt_me_writer_removed_unexpected_total 621
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2176
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1720
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26501
telemt_me_writer_teardown_success_total{mode="normal"} 28943
telemt_me_writer_teardown_noop_total 28301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57244
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.136190
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57244
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 747507
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 13868321413 (12.92 GB)
telemt_user_octets_to_client{user="hello"} 349123073187 (325.15 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 150638.3 (41h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11928650
telemt_connections_bad_total 1388159
telemt_connections_current 6027
telemt_connections_me_current 6027
telemt_handshake_timeouts_total 326362
telemt_upstream_connect_attempt_total 56626
telemt_upstream_connect_success_total 56403
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 56576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 2210
telemt_me_reconnect_success_total 1186
telemt_me_reader_eof_total 1148
telemt_me_idle_close_by_peer_total 1148
telemt_me_route_drop_no_conn_total 3861388
telemt_me_route_drop_channel_closed_total 114
telemt_me_route_drop_queue_full_total 35
telemt_me_route_drop_queue_full_profile_total{profile="high"} 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8989594
telemt_me_endpoint_quarantine_total 1029
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1129
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
telemt_me_writers_active_current 46
telemt_desync_total 36929
telemt_desync_full_logged_total 12085
telemt_desync_suppressed_total 24844
telemt_desync_frames_bucket_total{bucket="1_2"} 8816
telemt_desync_frames_bucket_total{bucket="3_10"} 13684
telemt_desync_frames_bucket_total{bucket="gt_10"} 14429
telemt_pool_swap_total 167
telemt_pool_force_close_total 4614
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 587
telemt_me_draining_writers_reap_progress_total 51000
telemt_me_writer_removed_unexpected_total 1104
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4195
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47939
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4449
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 165
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46386
telemt_me_writer_teardown_success_total{mode="normal"} 52134
telemt_me_writer_teardown_noop_total 51002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.298244
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 587
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1040
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8959473
telemt_user_connections_current{user="hello"} 6027
telemt_user_octets_from_client{user="hello"} 172521420468 (160.67 GB)
telemt_user_octets_to_client{user="hello"} 4002285530008 (3.64 TB)
telemt_user_unique_ips_current{user="hello"} 2146
telemt_user_unique_ips_recent_window{user="hello"} 719
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 150634.7 (41h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10309977
telemt_connections_bad_total 1154873
telemt_connections_current 4663
telemt_connections_me_current 4663
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 268299
telemt_upstream_connect_attempt_total 82166
telemt_upstream_connect_success_total 81557
telemt_upstream_connect_fail_total 528
telemt_upstream_connect_attempts_per_request{bucket="1"} 82085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 528
telemt_me_reconnect_attempts_total 8713
telemt_me_reconnect_success_total 1968
telemt_me_reader_eof_total 1831
telemt_me_idle_close_by_peer_total 1831
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4808350
telemt_me_route_drop_channel_closed_total 328
telemt_me_route_drop_queue_full_total 17
telemt_me_route_drop_queue_full_profile_total{profile="high"} 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7947844
telemt_me_endpoint_quarantine_total 1149
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1134
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
telemt_me_writers_active_current 44
telemt_desync_total 36312
telemt_desync_full_logged_total 11785
telemt_desync_suppressed_total 24527
telemt_desync_frames_bucket_total{bucket="1_2"} 8989
telemt_desync_frames_bucket_total{bucket="3_10"} 13546
telemt_desync_frames_bucket_total{bucket="gt_10"} 13777
telemt_pool_swap_total 160
telemt_pool_force_close_total 4472
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 50287
telemt_me_writer_removed_unexpected_total 1856
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46988
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4063
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45815
telemt_me_writer_teardown_success_total{mode="normal"} 52210
telemt_me_writer_teardown_noop_total 50291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102501
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.703979
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102501
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 346
telemt_me_writer_restored_same_endpoint_total 1592
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 7954415
telemt_user_connections_current{user="hello"} 4663
telemt_user_octets_from_client{user="hello"} 139765703161 (130.17 GB)
telemt_user_octets_to_client{user="hello"} 3090790461743 (2.81 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1768
telemt_user_unique_ips_recent_window{user="hello"} 667
```