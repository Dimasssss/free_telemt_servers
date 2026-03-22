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

# Server Metrics 2026-03-22 09:04:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 43069.3 (11h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1054828
telemt_connections_bad_total 59008
telemt_connections_current 1838
telemt_connections_me_current 1838
telemt_handshake_timeouts_total 48080
telemt_upstream_connect_attempt_total 16984
telemt_upstream_connect_success_total 16983
telemt_upstream_connect_attempts_per_request{bucket="1"} 16983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11018
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 261
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 576564
telemt_me_route_drop_channel_closed_total 203
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 877750
telemt_me_endpoint_quarantine_total 303
telemt_me_single_endpoint_shadow_rotate_total 346
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
telemt_desync_total 6418
telemt_desync_full_logged_total 1821
telemt_desync_suppressed_total 4597
telemt_desync_frames_bucket_total{bucket="1_2"} 1922
telemt_desync_frames_bucket_total{bucket="3_10"} 2415
telemt_desync_frames_bucket_total{bucket="gt_10"} 2081
telemt_pool_swap_total 47
telemt_pool_force_close_total 1330
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 151
telemt_me_draining_writers_reap_progress_total 15434
telemt_me_writer_removed_unexpected_total 256
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1063
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14578
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14104
telemt_me_writer_teardown_success_total{mode="normal"} 15641
telemt_me_writer_teardown_noop_total 15436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31077
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.273883
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31077
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 151
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 239
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 876149
telemt_user_connections_current{user="hello"} 1838
telemt_user_octets_from_client{user="hello"} 12738764504 (11.86 GB)
telemt_user_octets_to_client{user="hello"} 281772034560 (262.42 GB)
telemt_user_unique_ips_current{user="hello"} 666
telemt_user_unique_ips_recent_window{user="hello"} 287
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 56435.9 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1584531
telemt_connections_bad_total 153775
telemt_connections_current 1343
telemt_connections_me_current 1343
telemt_handshake_timeouts_total 43678
telemt_upstream_connect_attempt_total 33912
telemt_upstream_connect_success_total 33476
telemt_upstream_connect_fail_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 33858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 382
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2505
telemt_me_reconnect_success_total 1075
telemt_me_reader_eof_total 976
telemt_me_idle_close_by_peer_total 976
telemt_me_route_drop_no_conn_total 766367
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1197631
telemt_me_endpoint_quarantine_total 493
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 447
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 5362
telemt_desync_full_logged_total 3098
telemt_desync_suppressed_total 2264
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 2084
telemt_desync_frames_bucket_total{bucket="gt_10"} 2105
telemt_pool_swap_total 58
telemt_pool_force_close_total 1581
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 22967
telemt_me_writer_removed_unexpected_total 944
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2270
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21632
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21386
telemt_me_writer_teardown_success_total{mode="normal"} 23902
telemt_me_writer_teardown_noop_total 22967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46869
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.133825
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46869
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 865
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1203806
telemt_user_connections_current{user="hello"} 1343
telemt_user_octets_from_client{user="hello"} 18210387630 (16.96 GB)
telemt_user_octets_to_client{user="hello"} 401151289652 (373.60 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 891
telemt_user_unique_ips_recent_window{user="hello"} 691
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 131295.6 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10028489
telemt_connections_bad_total 891866
telemt_connections_current 5103
telemt_connections_me_current 5103
telemt_handshake_timeouts_total 295956
telemt_upstream_connect_attempt_total 48310
telemt_upstream_connect_success_total 48230
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1947
telemt_me_reconnect_success_total 997
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1005
telemt_me_route_drop_no_conn_total 5873828
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7885345
telemt_me_endpoint_quarantine_total 820
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 982
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
telemt_me_writers_active_current 47
telemt_desync_total 34095
telemt_desync_full_logged_total 11160
telemt_desync_suppressed_total 22935
telemt_desync_frames_bucket_total{bucket="1_2"} 7511
telemt_desync_frames_bucket_total{bucket="3_10"} 13280
telemt_desync_frames_bucket_total{bucket="gt_10"} 13304
telemt_pool_swap_total 141
telemt_pool_force_close_total 4712
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 720
telemt_me_draining_writers_reap_progress_total 44093
telemt_me_writer_removed_unexpected_total 967
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40808
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4397
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 315
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39381
telemt_me_writer_teardown_success_total{mode="normal"} 44516
telemt_me_writer_teardown_noop_total 44137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88653
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 191.318741
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88653
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 720
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 893
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 7875385
telemt_user_connections_current{user="hello"} 5103
telemt_user_octets_from_client{user="hello"} 128482711120 (119.66 GB)
telemt_user_octets_to_client{user="hello"} 2585025470812 (2.35 TB)
telemt_user_unique_ips_current{user="hello"} 1970
telemt_user_unique_ips_recent_window{user="hello"} 995
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 131296.8 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8129734
telemt_connections_bad_total 729562
telemt_connections_current 3828
telemt_connections_me_current 3828
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 259270
telemt_upstream_connect_attempt_total 54311
telemt_upstream_connect_success_total 53830
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 54076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2924
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 1018
telemt_me_idle_close_by_peer_total 1018
telemt_me_route_drop_no_conn_total 2766553
telemt_me_route_drop_channel_closed_total 324
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6012730
telemt_me_endpoint_quarantine_total 832
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1011
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
telemt_me_writers_active_current 46
telemt_desync_total 27674
telemt_desync_full_logged_total 9400
telemt_desync_suppressed_total 18274
telemt_desync_frames_bucket_total{bucket="1_2"} 6682
telemt_desync_frames_bucket_total{bucket="3_10"} 10709
telemt_desync_frames_bucket_total{bucket="gt_10"} 10283
telemt_pool_swap_total 143
telemt_pool_force_close_total 4301
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 465
telemt_me_draining_writers_reap_progress_total 42297
telemt_me_writer_removed_unexpected_total 1036
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3611
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39615
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4047
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 254
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37996
telemt_me_writer_teardown_success_total{mode="normal"} 43226
telemt_me_writer_teardown_noop_total 42303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85529
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 60.101032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85529
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 465
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 926
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5935194
telemt_user_connections_current{user="hello"} 3828
telemt_user_octets_from_client{user="hello"} 163004831887 (151.81 GB)
telemt_user_octets_to_client{user="hello"} 2838875970734 (2.58 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1481
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 131261.3 (36h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7793550
telemt_connections_bad_total 646839
telemt_connections_current 4757
telemt_connections_me_current 4757
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 258545
telemt_upstream_connect_attempt_total 58841
telemt_upstream_connect_success_total 58158
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 58305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1323
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2895
telemt_me_reconnect_success_total 1272
telemt_me_reader_eof_total 1167
telemt_me_idle_close_by_peer_total 1167
telemt_me_route_drop_no_conn_total 3148067
telemt_me_route_drop_channel_closed_total 197
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5814391
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 965
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
telemt_me_writers_active_current 85
telemt_desync_total 27235
telemt_desync_full_logged_total 9289
telemt_desync_suppressed_total 17946
telemt_desync_frames_bucket_total{bucket="1_2"} 6568
telemt_desync_frames_bucket_total{bucket="3_10"} 10452
telemt_desync_frames_bucket_total{bucket="gt_10"} 10215
telemt_pool_swap_total 139
telemt_pool_force_close_total 4147
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 43284
telemt_me_writer_removed_unexpected_total 1184
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3885
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39137
telemt_me_writer_teardown_success_total{mode="normal"} 44452
telemt_me_writer_teardown_noop_total 43296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87748
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.987314
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87748
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1109
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 5807252
telemt_user_connections_current{user="hello"} 4757
telemt_user_octets_from_client{user="hello"} 149477365567 (139.21 GB)
telemt_user_octets_to_client{user="hello"} 2574187082371 (2.34 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1957
telemt_user_unique_ips_recent_window{user="hello"} 603
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 1541.3 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 594167
telemt_connections_bad_total 53809
telemt_connections_current 6741
telemt_connections_me_current 6741
telemt_handshake_timeouts_total 6775
telemt_upstream_connect_attempt_total 593
telemt_upstream_connect_success_total 557
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 1237404
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485114
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 903
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 679
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 365
telemt_pool_force_close_total 2
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 337
telemt_me_writer_removed_unexpected_total 50
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 324
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 335
telemt_me_writer_teardown_success_total{mode="normal"} 387
telemt_me_writer_teardown_noop_total 337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 724
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.274443
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 724
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 485082
telemt_user_connections_current{user="hello"} 6741
telemt_user_octets_from_client{user="hello"} 3260585300 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 16615716616 (15.47 GB)
telemt_user_unique_ips_current{user="hello"} 2330
telemt_user_unique_ips_recent_window{user="hello"} 1367
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 131267.8 (36h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7429556
telemt_connections_bad_total 669583
telemt_connections_current 4242
telemt_connections_me_current 4242
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 152436
telemt_upstream_connect_attempt_total 75027
telemt_upstream_connect_success_total 74209
telemt_upstream_connect_fail_total 700
telemt_upstream_connect_attempts_per_request{bucket="1"} 74909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 442
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 700
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70387
telemt_me_reconnect_success_total 2029
telemt_me_reader_eof_total 1773
telemt_me_idle_close_by_peer_total 1772
telemt_me_route_drop_no_conn_total 2918829
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5835043
telemt_me_endpoint_quarantine_total 885
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 991
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
telemt_me_writers_active_current 49
telemt_desync_total 29429
telemt_desync_full_logged_total 10230
telemt_desync_suppressed_total 19199
telemt_desync_frames_bucket_total{bucket="1_2"} 5873
telemt_desync_frames_bucket_total{bucket="3_10"} 11327
telemt_desync_frames_bucket_total{bucket="gt_10"} 12229
telemt_pool_swap_total 137
telemt_pool_force_close_total 3932
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 466
telemt_me_draining_writers_reap_progress_total 45468
telemt_me_writer_removed_unexpected_total 1803
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4603
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42694
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3490
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 442
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41536
telemt_me_writer_teardown_success_total{mode="normal"} 47297
telemt_me_writer_teardown_noop_total 45469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92766
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.374397
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92766
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 466
telemt_me_refill_failed_total 4229
telemt_me_writer_restored_same_endpoint_total 1677
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 5833161
telemt_user_connections_current{user="hello"} 4242
telemt_user_octets_from_client{user="hello"} 147484987963 (137.36 GB)
telemt_user_octets_to_client{user="hello"} 2405426890631 (2.19 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1586
telemt_user_unique_ips_recent_window{user="hello"} 715
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 68104.1 (18h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5934637
telemt_connections_bad_total 232525
telemt_connections_current 5165
telemt_connections_me_current 5165
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2356768
telemt_upstream_connect_attempt_total 36473
telemt_upstream_connect_success_total 36218
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 36466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_reconnect_attempts_total 47424
telemt_me_reconnect_success_total 1231
telemt_me_reader_eof_total 900
telemt_me_idle_close_by_peer_total 900
telemt_me_route_drop_no_conn_total 1508124
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2981942
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 519
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
telemt_me_writers_active_current 91
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 16332
telemt_desync_full_logged_total 5532
telemt_desync_suppressed_total 10800
telemt_desync_frames_bucket_total{bucket="1_2"} 3215
telemt_desync_frames_bucket_total{bucket="3_10"} 6293
telemt_desync_frames_bucket_total{bucket="gt_10"} 6824
telemt_pool_swap_total 72
telemt_pool_force_close_total 2160
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 24476
telemt_me_writer_removed_unexpected_total 971
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2136
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23333
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 278
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22316
telemt_me_writer_teardown_success_total{mode="normal"} 25469
telemt_me_writer_teardown_noop_total 24482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49951
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.617942
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49951
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 2687
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 2982924
telemt_user_connections_current{user="hello"} 5165
telemt_user_octets_from_client{user="hello"} 75617511700 (70.42 GB)
telemt_user_octets_to_client{user="hello"} 1296160489106 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2045
telemt_user_unique_ips_recent_window{user="hello"} 709
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 49074.6 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445489
telemt_connections_bad_total 3082
telemt_connections_current 946
telemt_connections_me_current 946
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8647
telemt_upstream_connect_attempt_total 26074
telemt_upstream_connect_success_total 26014
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 26069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 257
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 1024
telemt_me_reconnect_success_total 397
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 143295
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402384
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 423
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
telemt_me_writers_active_current 43
telemt_desync_total 1851
telemt_desync_full_logged_total 541
telemt_desync_suppressed_total 1310
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 723
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 53
telemt_pool_force_close_total 1222
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 20994
telemt_me_writer_removed_unexpected_total 376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1487
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19900
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1194
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19772
telemt_me_writer_teardown_success_total{mode="normal"} 21387
telemt_me_writer_teardown_noop_total 20994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.967323
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42381
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 346
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 404517
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 8019333101 (7.47 GB)
telemt_user_octets_to_client{user="hello"} 203579958539 (189.60 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 131272.2 (36h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9152008
telemt_connections_bad_total 1058900
telemt_connections_current 5228
telemt_connections_me_current 5228
telemt_handshake_timeouts_total 251804
telemt_upstream_connect_attempt_total 50907
telemt_upstream_connect_success_total 50713
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 50863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_reconnect_attempts_total 1907
telemt_me_reconnect_success_total 1038
telemt_me_reader_eof_total 1009
telemt_me_idle_close_by_peer_total 1009
telemt_me_route_drop_no_conn_total 2575845
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6780301
telemt_me_endpoint_quarantine_total 930
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 997
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 27295
telemt_desync_full_logged_total 8941
telemt_desync_suppressed_total 18354
telemt_desync_frames_bucket_total{bucket="1_2"} 6768
telemt_desync_frames_bucket_total{bucket="3_10"} 9940
telemt_desync_frames_bucket_total{bucket="gt_10"} 10587
telemt_pool_swap_total 145
telemt_pool_force_close_total 3902
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 474
telemt_me_draining_writers_reap_progress_total 45925
telemt_me_writer_removed_unexpected_total 970
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3670
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43255
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42023
telemt_me_writer_teardown_success_total{mode="normal"} 46925
telemt_me_writer_teardown_noop_total 45927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92852
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.627507
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92852
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 474
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 910
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6753203
telemt_user_connections_current{user="hello"} 5228
telemt_user_octets_from_client{user="hello"} 131341285664 (122.32 GB)
telemt_user_octets_to_client{user="hello"} 3171160735096 (2.88 TB)
telemt_user_unique_ips_current{user="hello"} 1859
telemt_user_unique_ips_recent_window{user="hello"} 758
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 131268.8 (36h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7944521
telemt_connections_bad_total 885959
telemt_connections_current 5247
telemt_connections_me_current 5247
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 210037
telemt_upstream_connect_attempt_total 66947
telemt_upstream_connect_success_total 66428
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 66880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 631
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_reconnect_attempts_total 6403
telemt_me_reconnect_success_total 1470
telemt_me_reader_eof_total 1319
telemt_me_idle_close_by_peer_total 1319
telemt_me_seq_mismatch_total 62
telemt_me_route_drop_no_conn_total 2735375
telemt_me_route_drop_channel_closed_total 234
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6050160
telemt_me_endpoint_quarantine_total 1023
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 994
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
telemt_desync_total 26220
telemt_desync_full_logged_total 8717
telemt_desync_suppressed_total 17503
telemt_desync_frames_bucket_total{bucket="1_2"} 6455
telemt_desync_frames_bucket_total{bucket="3_10"} 9629
telemt_desync_frames_bucket_total{bucket="gt_10"} 10136
telemt_pool_swap_total 142
telemt_pool_force_close_total 3848
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 468
telemt_me_draining_writers_reap_progress_total 44556
telemt_me_writer_removed_unexpected_total 1335
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4274
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41679
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 273
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40708
telemt_me_writer_teardown_success_total{mode="normal"} 45953
telemt_me_writer_teardown_noop_total 44560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90513
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.245254
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 468
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 1151
telemt_me_writer_restored_fallback_total 86
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 6050824
telemt_user_connections_current{user="hello"} 5247
telemt_user_octets_from_client{user="hello"} 111391711673 (103.74 GB)
telemt_user_octets_to_client{user="hello"} 2604330064884 (2.37 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1930
telemt_user_unique_ips_recent_window{user="hello"} 726
```