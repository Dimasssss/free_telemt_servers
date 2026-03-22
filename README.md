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

# Server Metrics 2026-03-22 06:00:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 32039.8 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 575470
telemt_connections_bad_total 37164
telemt_connections_current 1452
telemt_connections_me_current 1452
telemt_handshake_timeouts_total 29378
telemt_upstream_connect_attempt_total 13125
telemt_upstream_connect_success_total 13124
telemt_upstream_connect_attempts_per_request{bucket="1"} 13124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 354
telemt_me_reconnect_success_total 204
telemt_me_reader_eof_total 200
telemt_me_idle_close_by_peer_total 200
telemt_me_route_drop_no_conn_total 129616
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474085
telemt_me_endpoint_quarantine_total 239
telemt_me_single_endpoint_shadow_rotate_total 266
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
telemt_me_writers_active_current 44
telemt_desync_total 4142
telemt_desync_full_logged_total 1151
telemt_desync_suppressed_total 2991
telemt_desync_frames_bucket_total{bucket="1_2"} 1386
telemt_desync_frames_bucket_total{bucket="3_10"} 1572
telemt_desync_frames_bucket_total{bucket="gt_10"} 1184
telemt_pool_swap_total 35
telemt_pool_force_close_total 935
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 11886
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 816
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11255
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 925
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10951
telemt_me_writer_teardown_success_total{mode="normal"} 12071
telemt_me_writer_teardown_noop_total 11887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23958
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.412067
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23958
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 185
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 473063
telemt_user_connections_current{user="hello"} 1452
telemt_user_octets_from_client{user="hello"} 6321075956 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 171451578284 (159.68 GB)
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 45406.2 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1041579
telemt_connections_bad_total 91684
telemt_connections_current 998
telemt_connections_me_current 998
telemt_handshake_timeouts_total 34691
telemt_upstream_connect_attempt_total 24025
telemt_upstream_connect_success_total 23695
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 23993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_reconnect_attempts_total 1807
telemt_me_reconnect_success_total 653
telemt_me_reader_eof_total 577
telemt_me_idle_close_by_peer_total 577
telemt_me_route_drop_no_conn_total 388044
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 798082
telemt_me_endpoint_quarantine_total 420
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 368
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
telemt_desync_total 3380
telemt_desync_full_logged_total 1965
telemt_desync_suppressed_total 1415
telemt_desync_frames_bucket_total{bucket="1_2"} 708
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 1369
telemt_pool_swap_total 49
telemt_pool_force_close_total 1287
telemt_me_writer_close_signal_drop_total 97
telemt_me_draining_writers_reap_progress_total 18705
telemt_me_writer_removed_unexpected_total 551
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1601
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17668
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17418
telemt_me_writer_teardown_success_total{mode="normal"} 19269
telemt_me_writer_teardown_noop_total 18705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37974
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.395685
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37974
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 97
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 799755
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 13178158547 (12.27 GB)
telemt_user_octets_to_client{user="hello"} 295481531186 (275.19 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 401
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 120266.0 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8416773
telemt_connections_bad_total 738718
telemt_connections_current 3476
telemt_connections_me_current 3476
telemt_handshake_timeouts_total 272683
telemt_upstream_connect_attempt_total 44726
telemt_upstream_connect_success_total 44647
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1709
telemt_me_reconnect_success_total 874
telemt_me_reader_eof_total 885
telemt_me_idle_close_by_peer_total 885
telemt_me_route_drop_no_conn_total 4673335
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6731576
telemt_me_endpoint_quarantine_total 764
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 905
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 28534
telemt_desync_full_logged_total 9501
telemt_desync_suppressed_total 19033
telemt_desync_frames_bucket_total{bucket="1_2"} 6185
telemt_desync_frames_bucket_total{bucket="3_10"} 11144
telemt_desync_frames_bucket_total{bucket="gt_10"} 11205
telemt_pool_swap_total 130
telemt_pool_force_close_total 4293
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 648
telemt_me_draining_writers_reap_progress_total 40831
telemt_me_writer_removed_unexpected_total 853
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3376
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37812
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4044
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 249
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36538
telemt_me_writer_teardown_success_total{mode="normal"} 41188
telemt_me_writer_teardown_noop_total 40875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82063
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 169.516430
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82063
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 648
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 781
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 6722823
telemt_user_connections_current{user="hello"} 3476
telemt_user_octets_from_client{user="hello"} 114704487056 (106.83 GB)
telemt_user_octets_to_client{user="hello"} 2292663884636 (2.09 TB)
telemt_user_unique_ips_current{user="hello"} 1440
telemt_user_unique_ips_recent_window{user="hello"} 583
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 120267.1 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6940472
telemt_connections_bad_total 620344
telemt_connections_current 3504
telemt_connections_me_current 3504
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 232178
telemt_upstream_connect_attempt_total 48657
telemt_upstream_connect_success_total 48255
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 48460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2057
telemt_me_reconnect_success_total 933
telemt_me_reader_eof_total 912
telemt_me_idle_close_by_peer_total 912
telemt_me_route_drop_no_conn_total 2366441
telemt_me_route_drop_channel_closed_total 289
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5176414
telemt_me_endpoint_quarantine_total 761
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 927
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 23940
telemt_desync_full_logged_total 8232
telemt_desync_suppressed_total 15708
telemt_desync_frames_bucket_total{bucket="1_2"} 5727
telemt_desync_frames_bucket_total{bucket="3_10"} 9308
telemt_desync_frames_bucket_total{bucket="gt_10"} 8905
telemt_pool_swap_total 131
telemt_pool_force_close_total 3898
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 39246
telemt_me_writer_removed_unexpected_total 890
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36828
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35348
telemt_me_writer_teardown_success_total{mode="normal"} 40064
telemt_me_writer_teardown_noop_total 39252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79316
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.277929
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79316
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 814
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5097736
telemt_user_connections_current{user="hello"} 3504
telemt_user_octets_from_client{user="hello"} 147766734533 (137.62 GB)
telemt_user_octets_to_client{user="hello"} 2445094950351 (2.22 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1351
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 120235.2 (33h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6757573
telemt_connections_bad_total 568518
telemt_connections_current 2783
telemt_connections_me_current 2783
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 226493
telemt_upstream_connect_attempt_total 55102
telemt_upstream_connect_success_total 54522
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 54666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2530
telemt_me_reconnect_success_total 1094
telemt_me_reader_eof_total 1025
telemt_me_idle_close_by_peer_total 1025
telemt_me_route_drop_no_conn_total 2389984
telemt_me_route_drop_channel_closed_total 150
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5025134
telemt_me_endpoint_quarantine_total 856
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 893
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
telemt_me_writers_active_current 43
telemt_desync_total 23784
telemt_desync_full_logged_total 8084
telemt_desync_suppressed_total 15700
telemt_desync_frames_bucket_total{bucket="1_2"} 5783
telemt_desync_frames_bucket_total{bucket="3_10"} 9125
telemt_desync_frames_bucket_total{bucket="gt_10"} 8876
telemt_pool_swap_total 129
telemt_pool_force_close_total 3764
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 40217
telemt_me_writer_removed_unexpected_total 1015
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3487
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37761
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3517
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36453
telemt_me_writer_teardown_success_total{mode="normal"} 41248
telemt_me_writer_teardown_noop_total 40229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.048010
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 950
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 5019423
telemt_user_connections_current{user="hello"} 2783
telemt_user_octets_from_client{user="hello"} 138634058303 (129.11 GB)
telemt_user_octets_to_client{user="hello"} 2292728004195 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1188
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 120270.8 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21583325
telemt_connections_bad_total 1830968
telemt_connections_current 4443
telemt_connections_me_current 4443
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 656711
telemt_upstream_connect_attempt_total 210963
telemt_upstream_connect_success_total 192281
telemt_upstream_connect_fail_total 16763
telemt_upstream_connect_attempts_per_request{bucket="1"} 209044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47144
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9878
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16763
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65508
telemt_me_reconnect_success_total 2557
telemt_me_reader_eof_total 1601
telemt_me_idle_close_by_peer_total 1600
telemt_me_route_drop_no_conn_total 40753371
telemt_me_route_drop_channel_closed_total 131
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17347397
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 936
telemt_me_single_endpoint_outage_enter_total 153
telemt_me_single_endpoint_outage_exit_total 153
telemt_me_single_endpoint_outage_reconnect_attempt_total 322
telemt_me_single_endpoint_outage_reconnect_success_total 80
telemt_me_single_endpoint_quarantine_bypass_total 322
telemt_me_single_endpoint_shadow_rotate_total 946
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
telemt_me_writers_active_current 45
telemt_desync_total 33501
telemt_desync_full_logged_total 10085
telemt_desync_suppressed_total 23416
telemt_desync_frames_bucket_total{bucket="1_2"} 7357
telemt_desync_frames_bucket_total{bucket="3_10"} 14867
telemt_desync_frames_bucket_total{bucket="gt_10"} 11277
telemt_pool_swap_total 124
telemt_pool_force_close_total 3977
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 878
telemt_me_draining_writers_reap_progress_total 37821
telemt_me_writer_removed_unexpected_total 2379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34833
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 561
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33844
telemt_me_writer_teardown_success_total{mode="normal"} 39949
telemt_me_writer_teardown_noop_total 37848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77797
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 219.257236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77797
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 878
telemt_me_refill_failed_total 3814
telemt_me_writer_restored_same_endpoint_total 1739
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 17486693
telemt_user_connections_current{user="hello"} 4443
telemt_user_octets_from_client{user="hello"} 258292458861 (240.55 GB)
telemt_user_octets_to_client{user="hello"} 1350675266067 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 409002
telemt_user_msgs_to_client{user="hello"} 794272
telemt_user_unique_ips_current{user="hello"} 1754
telemt_user_unique_ips_recent_window{user="hello"} 722
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 120237.9 (33h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6516856
telemt_connections_bad_total 616164
telemt_connections_current 3140
telemt_connections_me_current 3140
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 136783
telemt_upstream_connect_attempt_total 63721
telemt_upstream_connect_success_total 62983
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 63614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_reconnect_attempts_total 69948
telemt_me_reconnect_success_total 1902
telemt_me_reader_eof_total 1677
telemt_me_idle_close_by_peer_total 1676
telemt_me_route_drop_no_conn_total 2501434
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5076269
telemt_me_endpoint_quarantine_total 811
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 914
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
telemt_me_writers_active_current 45
telemt_desync_total 25219
telemt_desync_full_logged_total 8833
telemt_desync_suppressed_total 16386
telemt_desync_frames_bucket_total{bucket="1_2"} 4997
telemt_desync_frames_bucket_total{bucket="3_10"} 9731
telemt_desync_frames_bucket_total{bucket="gt_10"} 10491
telemt_pool_swap_total 125
telemt_pool_force_close_total 3580
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 422
telemt_me_draining_writers_reap_progress_total 42389
telemt_me_writer_removed_unexpected_total 1710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4268
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39866
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3174
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38809
telemt_me_writer_teardown_success_total{mode="normal"} 44134
telemt_me_writer_teardown_noop_total 42390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86524
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.640353
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86524
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 422
telemt_me_refill_failed_total 4215
telemt_me_writer_restored_same_endpoint_total 1588
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 5068180
telemt_user_connections_current{user="hello"} 3140
telemt_user_octets_from_client{user="hello"} 130702197756 (121.73 GB)
telemt_user_octets_to_client{user="hello"} 2114451799434 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1356
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 57073.8 (15h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4578016
telemt_connections_bad_total 189504
telemt_connections_current 2858
telemt_connections_me_current 2858
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1811611
telemt_upstream_connect_attempt_total 32541
telemt_upstream_connect_success_total 32324
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 32534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_reconnect_attempts_total 46106
telemt_me_reconnect_success_total 1040
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 731
telemt_me_route_drop_no_conn_total 1136713
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2267526
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 444
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12120
telemt_desync_full_logged_total 4164
telemt_desync_suppressed_total 7956
telemt_desync_frames_bucket_total{bucket="1_2"} 2331
telemt_desync_frames_bucket_total{bucket="3_10"} 4635
telemt_desync_frames_bucket_total{bucket="gt_10"} 5154
telemt_pool_swap_total 62
telemt_pool_force_close_total 1820
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 21110
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1796
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20145
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19290
telemt_me_writer_teardown_success_total{mode="normal"} 21941
telemt_me_writer_teardown_noop_total 21112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43053
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.707023
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43053
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 2618
telemt_me_writer_restored_same_endpoint_total 928
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2269733
telemt_user_connections_current{user="hello"} 2858
telemt_user_octets_from_client{user="hello"} 60039414280 (55.92 GB)
telemt_user_octets_to_client{user="hello"} 1003311940458 (934.41 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1189
telemt_user_unique_ips_recent_window{user="hello"} 465
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 38044.7 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275105
telemt_connections_bad_total 2012
telemt_connections_current 569
telemt_connections_me_current 569
telemt_handshake_timeouts_total 6834
telemt_upstream_connect_attempt_total 18345
telemt_upstream_connect_success_total 18300
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 18341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 480
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 78016
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246423
telemt_me_endpoint_quarantine_total 363
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 331
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
telemt_desync_total 1273
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 921
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 347
telemt_pool_swap_total 42
telemt_pool_force_close_total 936
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 16624
telemt_me_writer_removed_unexpected_total 241
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1067
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15809
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 934
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15688
telemt_me_writer_teardown_success_total{mode="normal"} 16876
telemt_me_writer_teardown_noop_total 16624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33500
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.305159
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33500
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 217
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 246020
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 4130690040 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 148910654956 (138.68 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 120242.4 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7903446
telemt_connections_bad_total 794770
telemt_connections_current 3425
telemt_connections_me_current 3425
telemt_handshake_timeouts_total 224556
telemt_upstream_connect_attempt_total 47341
telemt_upstream_connect_success_total 47170
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 47304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 1700
telemt_me_reconnect_success_total 917
telemt_me_reader_eof_total 910
telemt_me_idle_close_by_peer_total 910
telemt_me_route_drop_no_conn_total 2235897
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5892668
telemt_me_endpoint_quarantine_total 858
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 923
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
telemt_desync_total 23096
telemt_desync_full_logged_total 7618
telemt_desync_suppressed_total 15478
telemt_desync_frames_bucket_total{bucket="1_2"} 5773
telemt_desync_frames_bucket_total{bucket="3_10"} 8404
telemt_desync_frames_bucket_total{bucket="gt_10"} 8919
telemt_pool_swap_total 133
telemt_pool_force_close_total 3543
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 42747
telemt_me_writer_removed_unexpected_total 873
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3338
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40309
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3455
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39204
telemt_me_writer_teardown_success_total{mode="normal"} 43647
telemt_me_writer_teardown_noop_total 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86396
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.035614
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86396
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 820
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 5867116
telemt_user_connections_current{user="hello"} 3425
telemt_user_octets_from_client{user="hello"} 115372628356 (107.45 GB)
telemt_user_octets_to_client{user="hello"} 2751324861592 (2.50 TB)
telemt_user_unique_ips_current{user="hello"} 1346
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 120238.8 (33h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6868104
telemt_connections_bad_total 668068
telemt_connections_current 3576
telemt_connections_me_current 3576
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 185161
telemt_upstream_connect_attempt_total 63167
telemt_upstream_connect_success_total 62684
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 63104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_reconnect_attempts_total 5854
telemt_me_reconnect_success_total 1303
telemt_me_reader_eof_total 1170
telemt_me_idle_close_by_peer_total 1170
telemt_me_seq_mismatch_total 57
telemt_me_route_drop_no_conn_total 2291613
telemt_me_route_drop_channel_closed_total 192
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5260492
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 921
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
telemt_desync_total 22024
telemt_desync_full_logged_total 7322
telemt_desync_suppressed_total 14702
telemt_desync_frames_bucket_total{bucket="1_2"} 5523
telemt_desync_frames_bucket_total{bucket="3_10"} 8049
telemt_desync_frames_bucket_total{bucket="gt_10"} 8452
telemt_pool_swap_total 131
telemt_pool_force_close_total 3491
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 41263
telemt_me_writer_removed_unexpected_total 1183
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3903
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38602
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 224
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37772
telemt_me_writer_teardown_success_total{mode="normal"} 42505
telemt_me_writer_teardown_noop_total 41267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83772
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.891518
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83772
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 1014
telemt_me_writer_restored_fallback_total 76
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5262961
telemt_user_connections_current{user="hello"} 3576
telemt_user_octets_from_client{user="hello"} 98506793925 (91.74 GB)
telemt_user_octets_to_client{user="hello"} 2283595468792 (2.08 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1410
telemt_user_unique_ips_recent_window{user="hello"} 509
```