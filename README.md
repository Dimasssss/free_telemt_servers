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

# Server Metrics 2026-03-22 03:37:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 23452.5 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355601
telemt_connections_bad_total 23404
telemt_connections_current 1083
telemt_connections_me_current 1083
telemt_handshake_timeouts_total 20010
telemt_upstream_connect_attempt_total 9819
telemt_upstream_connect_success_total 9818
telemt_upstream_connect_attempts_per_request{bucket="1"} 9818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 278
telemt_me_reconnect_success_total 151
telemt_me_reader_eof_total 148
telemt_me_idle_close_by_peer_total 148
telemt_me_route_drop_no_conn_total 66568
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293506
telemt_me_endpoint_quarantine_total 186
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_warm_current 24
telemt_desync_total 2681
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1954
telemt_desync_frames_bucket_total{bucket="1_2"} 919
telemt_desync_frames_bucket_total{bucket="3_10"} 1005
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 25
telemt_pool_force_close_total 654
telemt_me_writer_close_signal_drop_total 46
telemt_me_draining_writers_reap_progress_total 8841
telemt_me_writer_removed_unexpected_total 146
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 591
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8388
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8187
telemt_me_writer_teardown_success_total{mode="normal"} 8979
telemt_me_writer_teardown_noop_total 8842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17821
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.022225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17821
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 46
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 137
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 292975
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 3875936760 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 102328919916 (95.30 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 36818.8 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 831829
telemt_connections_bad_total 53686
telemt_connections_current 824
telemt_connections_me_current 824
telemt_handshake_timeouts_total 30382
telemt_upstream_connect_attempt_total 17221
telemt_upstream_connect_success_total 16958
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 17198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_reconnect_attempts_total 1394
telemt_me_reconnect_success_total 529
telemt_me_reader_eof_total 468
telemt_me_idle_close_by_peer_total 468
telemt_me_route_drop_no_conn_total 347860
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658216
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 297
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
telemt_me_writers_active_current 46
telemt_desync_total 2809
telemt_desync_full_logged_total 1614
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 1069
telemt_desync_frames_bucket_total{bucket="gt_10"} 1145
telemt_pool_swap_total 39
telemt_pool_force_close_total 1049
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 15265
telemt_me_writer_removed_unexpected_total 445
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14455
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14216
telemt_me_writer_teardown_success_total{mode="normal"} 15720
telemt_me_writer_teardown_noop_total 15265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30985
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.788821
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30985
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 657267
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 10635005304 (9.90 GB)
telemt_user_octets_to_client{user="hello"} 234242104248 (218.15 GB)
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 111678.6 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7862222
telemt_connections_bad_total 650075
telemt_connections_current 2070
telemt_connections_me_current 2070
telemt_handshake_timeouts_total 258594
telemt_upstream_connect_attempt_total 41618
telemt_upstream_connect_success_total 41542
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 41549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1600
telemt_me_reconnect_success_total 837
telemt_me_reader_eof_total 846
telemt_me_idle_close_by_peer_total 846
telemt_me_route_drop_no_conn_total 4554001
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6352017
telemt_me_endpoint_quarantine_total 717
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 834
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 34
telemt_desync_total 26692
telemt_desync_full_logged_total 8855
telemt_desync_suppressed_total 17837
telemt_desync_frames_bucket_total{bucket="1_2"} 5764
telemt_desync_frames_bucket_total{bucket="3_10"} 10425
telemt_desync_frames_bucket_total{bucket="gt_10"} 10503
telemt_pool_swap_total 120
telemt_pool_force_close_total 3962
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 608
telemt_me_draining_writers_reap_progress_total 37940
telemt_me_writer_removed_unexpected_total 814
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3160
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35129
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3722
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33978
telemt_me_writer_teardown_success_total{mode="normal"} 38289
telemt_me_writer_teardown_noop_total 37984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76273
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 161.805041
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76273
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 608
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 746
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6344047
telemt_user_connections_current{user="hello"} 2070
telemt_user_octets_from_client{user="hello"} 107719679860 (100.32 GB)
telemt_user_octets_to_client{user="hello"} 2124019013572 (1.93 TB)
telemt_user_unique_ips_current{user="hello"} 1055
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 111680.0 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6504305
telemt_connections_bad_total 591011
telemt_connections_current 1847
telemt_connections_me_current 1847
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 215541
telemt_upstream_connect_attempt_total 45591
telemt_upstream_connect_success_total 45198
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 45394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1959
telemt_me_reconnect_success_total 890
telemt_me_reader_eof_total 862
telemt_me_idle_close_by_peer_total 862
telemt_me_route_drop_no_conn_total 2273082
telemt_me_route_drop_channel_closed_total 272
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4848270
telemt_me_endpoint_quarantine_total 698
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 859
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_warm_current 33
telemt_desync_total 22839
telemt_desync_full_logged_total 7787
telemt_desync_suppressed_total 15052
telemt_desync_frames_bucket_total{bucket="1_2"} 5489
telemt_desync_frames_bucket_total{bucket="3_10"} 8879
telemt_desync_frames_bucket_total{bucket="gt_10"} 8471
telemt_pool_swap_total 121
telemt_pool_force_close_total 3594
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 368
telemt_me_draining_writers_reap_progress_total 36431
telemt_me_writer_removed_unexpected_total 846
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34197
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3381
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32837
telemt_me_writer_teardown_success_total{mode="normal"} 37215
telemt_me_writer_teardown_noop_total 36437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73652
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.463975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73652
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 368
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 779
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4770347
telemt_user_connections_current{user="hello"} 1847
telemt_user_octets_from_client{user="hello"} 141483045405 (131.77 GB)
telemt_user_octets_to_client{user="hello"} 2259012395463 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 876
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 111645.2 (31h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6372310
telemt_connections_bad_total 550293
telemt_connections_current 1587
telemt_connections_me_current 1587
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 207469
telemt_upstream_connect_attempt_total 51730
telemt_upstream_connect_success_total 51339
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 51476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1088
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2091
telemt_me_reconnect_success_total 932
telemt_me_reader_eof_total 879
telemt_me_idle_close_by_peer_total 879
telemt_me_route_drop_no_conn_total 2168777
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4733221
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 833
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
telemt_me_writers_warm_current 11
telemt_desync_total 22757
telemt_desync_full_logged_total 7672
telemt_desync_suppressed_total 15085
telemt_desync_frames_bucket_total{bucket="1_2"} 5553
telemt_desync_frames_bucket_total{bucket="3_10"} 8722
telemt_desync_frames_bucket_total{bucket="gt_10"} 8482
telemt_pool_swap_total 120
telemt_pool_force_close_total 3482
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 392
telemt_me_draining_writers_reap_progress_total 37548
telemt_me_writer_removed_unexpected_total 848
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35310
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34066
telemt_me_writer_teardown_success_total{mode="normal"} 38413
telemt_me_writer_teardown_noop_total 37560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75973
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.864020
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75973
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 392
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 809
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 4728601
telemt_user_connections_current{user="hello"} 1587
telemt_user_octets_from_client{user="hello"} 134779358211 (125.52 GB)
telemt_user_octets_to_client{user="hello"} 2171993613499 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 800
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 111683.4 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20591685
telemt_connections_bad_total 1675390
telemt_connections_current 2522
telemt_connections_me_current 2522
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 618703
telemt_upstream_connect_attempt_total 202506
telemt_upstream_connect_success_total 184238
telemt_upstream_connect_fail_total 16464
telemt_upstream_connect_attempts_per_request{bucket="1"} 200702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44072
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8948
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16464
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65124
telemt_me_reconnect_success_total 2397
telemt_me_reader_eof_total 1484
telemt_me_idle_close_by_peer_total 1483
telemt_me_route_drop_no_conn_total 39538818
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16604757
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 872
telemt_me_single_endpoint_outage_enter_total 143
telemt_me_single_endpoint_outage_exit_total 143
telemt_me_single_endpoint_outage_reconnect_attempt_total 296
telemt_me_single_endpoint_outage_reconnect_success_total 75
telemt_me_single_endpoint_quarantine_bypass_total 296
telemt_me_single_endpoint_shadow_rotate_total 878
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_me_writers_warm_current 26
telemt_desync_total 32207
telemt_desync_full_logged_total 9688
telemt_desync_suppressed_total 22519
telemt_desync_frames_bucket_total{bucket="1_2"} 6985
telemt_desync_frames_bucket_total{bucket="3_10"} 14289
telemt_desync_frames_bucket_total{bucket="gt_10"} 10933
telemt_pool_swap_total 115
telemt_pool_force_close_total 3715
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 825
telemt_me_draining_writers_reap_progress_total 35016
telemt_me_writer_removed_unexpected_total 2227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4744
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32240
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3190
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31301
telemt_me_writer_teardown_success_total{mode="normal"} 36984
telemt_me_writer_teardown_noop_total 35043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72027
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.964300
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72027
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 825
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1627
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 16739645
telemt_user_connections_current{user="hello"} 2522
telemt_user_octets_from_client{user="hello"} 229202453336 (213.46 GB)
telemt_user_octets_to_client{user="hello"} 1237972812291 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1124
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 111650.8 (31h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6130428
telemt_connections_bad_total 588890
telemt_connections_current 1966
telemt_connections_me_current 1966
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 129113
telemt_upstream_connect_attempt_total 60422
telemt_upstream_connect_success_total 59727
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 60320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24641
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_reconnect_attempts_total 69754
telemt_me_reconnect_success_total 1817
telemt_me_reader_eof_total 1600
telemt_me_idle_close_by_peer_total 1599
telemt_me_route_drop_no_conn_total 2403669
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4765007
telemt_me_endpoint_quarantine_total 755
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 846
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
telemt_me_writers_warm_current 14
telemt_desync_total 23719
telemt_desync_full_logged_total 8348
telemt_desync_suppressed_total 15371
telemt_desync_frames_bucket_total{bucket="1_2"} 4563
telemt_desync_frames_bucket_total{bucket="3_10"} 9190
telemt_desync_frames_bucket_total{bucket="gt_10"} 9966
telemt_pool_swap_total 115
telemt_pool_force_close_total 3293
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 39453
telemt_me_writer_removed_unexpected_total 1637
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37100
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2892
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36160
telemt_me_writer_teardown_success_total{mode="normal"} 41122
telemt_me_writer_teardown_noop_total 39454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.176316
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 4210
telemt_me_writer_restored_same_endpoint_total 1525
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4757726
telemt_user_connections_current{user="hello"} 1966
telemt_user_octets_from_client{user="hello"} 125754640964 (117.12 GB)
telemt_user_octets_to_client{user="hello"} 1946018952306 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 899
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 48486.7 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4059035
telemt_connections_bad_total 169515
telemt_connections_current 1374
telemt_connections_me_current 1374
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1636269
telemt_upstream_connect_attempt_total 29151
telemt_upstream_connect_success_total 28965
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 29144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 45882
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 674
telemt_me_idle_close_by_peer_total 674
telemt_me_route_drop_no_conn_total 1034663
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1985642
telemt_me_endpoint_quarantine_total 360
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 374
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10633
telemt_desync_full_logged_total 3682
telemt_desync_suppressed_total 6951
telemt_desync_frames_bucket_total{bucket="1_2"} 1924
telemt_desync_frames_bucket_total{bucket="3_10"} 4078
telemt_desync_frames_bucket_total{bucket="gt_10"} 4631
telemt_pool_swap_total 52
telemt_pool_force_close_total 1548
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 18046
telemt_me_writer_removed_unexpected_total 747
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1595
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1342
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16498
telemt_me_writer_teardown_success_total{mode="normal"} 18820
telemt_me_writer_teardown_noop_total 18048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36868
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.498618
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36868
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 2608
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1989164
telemt_user_connections_current{user="hello"} 1374
telemt_user_octets_from_client{user="hello"} 55084376284 (51.30 GB)
telemt_user_octets_to_client{user="hello"} 843545249298 (785.61 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 728
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 29457.8 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211812
telemt_connections_bad_total 1764
telemt_connections_current 357
telemt_connections_me_current 357
telemt_handshake_timeouts_total 5772
telemt_upstream_connect_attempt_total 14194
telemt_upstream_connect_success_total 14160
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 14192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 325
telemt_me_reconnect_success_total 184
telemt_me_reader_eof_total 189
telemt_me_idle_close_by_peer_total 189
telemt_me_route_drop_no_conn_total 58868
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187120
telemt_me_endpoint_quarantine_total 288
telemt_me_single_endpoint_shadow_rotate_total 256
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1081
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 803
telemt_desync_frames_bucket_total{bucket="1_2"} 397
telemt_desync_frames_bucket_total{bucket="3_10"} 410
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 32
telemt_pool_force_close_total 716
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 12836
telemt_me_writer_removed_unexpected_total 182
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 822
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12203
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 714
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12120
telemt_me_writer_teardown_success_total{mode="normal"} 13025
telemt_me_writer_teardown_noop_total 12836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25861
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.058409
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25861
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 166
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 186790
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 3272971844 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 115278581888 (107.36 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 111655.3 (31h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7448109
telemt_connections_bad_total 749981
telemt_connections_current 1775
telemt_connections_me_current 1775
telemt_handshake_timeouts_total 212236
telemt_upstream_connect_attempt_total 43892
telemt_upstream_connect_success_total 43733
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 43855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 864
telemt_me_reader_eof_total 848
telemt_me_idle_close_by_peer_total 848
telemt_me_route_drop_no_conn_total 2142523
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5553953
telemt_me_endpoint_quarantine_total 786
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 860
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
telemt_me_writers_warm_current 17
telemt_desync_total 21794
telemt_desync_full_logged_total 7148
telemt_desync_suppressed_total 14646
telemt_desync_frames_bucket_total{bucket="1_2"} 5477
telemt_desync_frames_bucket_total{bucket="3_10"} 7893
telemt_desync_frames_bucket_total{bucket="gt_10"} 8424
telemt_pool_swap_total 123
telemt_pool_force_close_total 3287
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 393
telemt_me_draining_writers_reap_progress_total 39596
telemt_me_writer_removed_unexpected_total 817
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3090
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37344
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36309
telemt_me_writer_teardown_success_total{mode="normal"} 40434
telemt_me_writer_teardown_noop_total 39598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.689241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 393
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 5528882
telemt_user_connections_current{user="hello"} 1775
telemt_user_octets_from_client{user="hello"} 110479089872 (102.89 GB)
telemt_user_octets_to_client{user="hello"} 2576562145856 (2.34 TB)
telemt_user_unique_ips_current{user="hello"} 862
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 111651.9 (31h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6448655
telemt_connections_bad_total 634923
telemt_connections_current 1800
telemt_connections_me_current 1800
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 174826
telemt_upstream_connect_attempt_total 59718
telemt_upstream_connect_success_total 59270
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 59659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_reconnect_attempts_total 5603
telemt_me_reconnect_success_total 1202
telemt_me_reader_eof_total 1085
telemt_me_idle_close_by_peer_total 1085
telemt_me_seq_mismatch_total 51
telemt_me_route_drop_no_conn_total 2195328
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4920025
telemt_me_endpoint_quarantine_total 880
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 853
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 12
telemt_desync_total 20407
telemt_desync_full_logged_total 6804
telemt_desync_suppressed_total 13603
telemt_desync_frames_bucket_total{bucket="1_2"} 5218
telemt_desync_frames_bucket_total{bucket="3_10"} 7446
telemt_desync_frames_bucket_total{bucket="gt_10"} 7743
telemt_pool_swap_total 121
telemt_pool_force_close_total 3242
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 38181
telemt_me_writer_removed_unexpected_total 1097
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3626
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35706
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34939
telemt_me_writer_teardown_success_total{mode="normal"} 39332
telemt_me_writer_teardown_noop_total 38185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77517
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.134661
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77517
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_restored_fallback_total 69
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4922960
telemt_user_connections_current{user="hello"} 1800
telemt_user_octets_from_client{user="hello"} 92853108629 (86.48 GB)
telemt_user_octets_to_client{user="hello"} 2105990015888 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 837
telemt_user_unique_ips_recent_window{user="hello"} 207
```