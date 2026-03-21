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

# Server Metrics 2026-03-21 22:46:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 6021.5 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106257
telemt_connections_bad_total 7792
telemt_connections_current 690
telemt_connections_me_current 690
telemt_handshake_timeouts_total 4998
telemt_upstream_connect_attempt_total 2354
telemt_upstream_connect_success_total 2353
telemt_upstream_connect_attempts_per_request{bucket="1"} 2353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 51
telemt_me_reconnect_success_total 32
telemt_me_reader_eof_total 33
telemt_me_idle_close_by_peer_total 33
telemt_me_route_drop_no_conn_total 21773
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86523
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 578
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 398
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 6
telemt_pool_force_close_total 161
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 2054
telemt_me_writer_removed_unexpected_total 31
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 153
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1934
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1893
telemt_me_writer_teardown_success_total{mode="normal"} 2087
telemt_me_writer_teardown_noop_total 2054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4141
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.461083
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4141
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 86443
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 1144563740 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 32884377980 (30.63 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 19387.9 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618352
telemt_connections_bad_total 28176
telemt_connections_current 486
telemt_connections_me_current 486
telemt_handshake_timeouts_total 22787
telemt_upstream_connect_attempt_total 7988
telemt_upstream_connect_success_total 7842
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 7973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_reconnect_attempts_total 649
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 205
telemt_me_idle_close_by_peer_total 205
telemt_me_route_drop_no_conn_total 316198
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504400
telemt_me_endpoint_quarantine_total 161
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 157
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 48
telemt_desync_total 2246
telemt_desync_full_logged_total 1280
telemt_desync_suppressed_total 966
telemt_desync_frames_bucket_total{bucket="1_2"} 470
telemt_desync_frames_bucket_total{bucket="3_10"} 851
telemt_desync_frames_bucket_total{bucket="gt_10"} 925
telemt_pool_swap_total 21
telemt_pool_force_close_total 601
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 7004
telemt_me_writer_removed_unexpected_total 194
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 614
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6582
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6403
telemt_me_writer_teardown_success_total{mode="normal"} 7196
telemt_me_writer_teardown_noop_total 7004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14200
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.187934
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14200
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 171
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 503738
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 8593018376 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 172911115600 (161.04 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 94247.9 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7288863
telemt_connections_bad_total 556804
telemt_connections_current 2050
telemt_connections_me_current 2050
telemt_handshake_timeouts_total 231097
telemt_upstream_connect_attempt_total 33969
telemt_upstream_connect_success_total 33901
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 33908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1465
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 4472950
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5965568
telemt_me_endpoint_quarantine_total 596
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 697
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
telemt_me_writers_active_current 46
telemt_desync_total 25281
telemt_desync_full_logged_total 8329
telemt_desync_suppressed_total 16952
telemt_desync_frames_bucket_total{bucket="1_2"} 5429
telemt_desync_frames_bucket_total{bucket="3_10"} 9882
telemt_desync_frames_bucket_total{bucket="gt_10"} 9970
telemt_pool_swap_total 101
telemt_pool_force_close_total 3419
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 558
telemt_me_draining_writers_reap_progress_total 30933
telemt_me_writer_removed_unexpected_total 700
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2642
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28568
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27514
telemt_me_writer_teardown_success_total{mode="normal"} 31210
telemt_me_writer_teardown_noop_total 30977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62187
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.316617
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62187
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 558
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5958281
telemt_user_connections_current{user="hello"} 2050
telemt_user_octets_from_client{user="hello"} 102269495108 (95.25 GB)
telemt_user_octets_to_client{user="hello"} 1936061652924 (1.76 TB)
telemt_user_unique_ips_current{user="hello"} 955
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 94249.0 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5990489
telemt_connections_bad_total 575135
telemt_connections_current 1844
telemt_connections_me_current 1844
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 196195
telemt_upstream_connect_attempt_total 37919
telemt_upstream_connect_success_total 37584
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 37759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1743
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 721
telemt_me_idle_close_by_peer_total 721
telemt_me_route_drop_no_conn_total 2109369
telemt_me_route_drop_channel_closed_total 242
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4478939
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 720
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
telemt_me_writers_active_current 44
telemt_desync_total 21554
telemt_desync_full_logged_total 7228
telemt_desync_suppressed_total 14326
telemt_desync_frames_bucket_total{bucket="1_2"} 5213
telemt_desync_frames_bucket_total{bucket="3_10"} 8343
telemt_desync_frames_bucket_total{bucket="gt_10"} 7998
telemt_pool_swap_total 103
telemt_pool_force_close_total 3115
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 29522
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2536
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27616
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26407
telemt_me_writer_teardown_success_total{mode="normal"} 30152
telemt_me_writer_teardown_noop_total 29528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59680
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.809007
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59680
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4438775
telemt_user_connections_current{user="hello"} 1844
telemt_user_octets_from_client{user="hello"} 136809074381 (127.41 GB)
telemt_user_octets_to_client{user="hello"} 2068813600575 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 848
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 94213.2 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5908990
telemt_connections_bad_total 533998
telemt_connections_current 1660
telemt_connections_me_current 1660
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 187296
telemt_upstream_connect_attempt_total 44288
telemt_upstream_connect_success_total 43991
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 44126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1045
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1784
telemt_me_reconnect_success_total 801
telemt_me_reader_eof_total 748
telemt_me_idle_close_by_peer_total 748
telemt_me_route_drop_no_conn_total 2079085
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4419729
telemt_me_endpoint_quarantine_total 631
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 702
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 21412
telemt_desync_full_logged_total 7049
telemt_desync_suppressed_total 14363
telemt_desync_frames_bucket_total{bucket="1_2"} 5276
telemt_desync_frames_bucket_total{bucket="3_10"} 8141
telemt_desync_frames_bucket_total{bucket="gt_10"} 7995
telemt_pool_swap_total 101
telemt_pool_force_close_total 2994
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 362
telemt_me_draining_writers_reap_progress_total 30925
telemt_me_writer_removed_unexpected_total 716
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2613
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29034
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27931
telemt_me_writer_teardown_success_total{mode="normal"} 31647
telemt_me_writer_teardown_noop_total 30936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62583
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.117352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62583
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 362
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 692
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4421297
telemt_user_connections_current{user="hello"} 1660
telemt_user_octets_from_client{user="hello"} 129896250327 (120.98 GB)
telemt_user_octets_to_client{user="hello"} 2020756311863 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 94252.9 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19735345
telemt_connections_bad_total 1401169
telemt_connections_current 2406
telemt_connections_me_current 2406
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 563143
telemt_upstream_connect_attempt_total 183999
telemt_upstream_connect_success_total 166665
telemt_upstream_connect_fail_total 15827
telemt_upstream_connect_attempts_per_request{bucket="1"} 182492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8858
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15827
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 63991
telemt_me_reconnect_success_total 2021
telemt_me_reader_eof_total 1293
telemt_me_idle_close_by_peer_total 1292
telemt_me_route_drop_no_conn_total 39415424
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16125394
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 704
telemt_me_single_endpoint_outage_enter_total 113
telemt_me_single_endpoint_outage_exit_total 113
telemt_me_single_endpoint_outage_reconnect_attempt_total 241
telemt_me_single_endpoint_outage_reconnect_success_total 55
telemt_me_single_endpoint_quarantine_bypass_total 241
telemt_me_single_endpoint_shadow_rotate_total 733
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
telemt_me_writers_active_current 51
telemt_desync_total 30979
telemt_desync_full_logged_total 9178
telemt_desync_suppressed_total 21801
telemt_desync_frames_bucket_total{bucket="1_2"} 6780
telemt_desync_frames_bucket_total{bucket="3_10"} 13723
telemt_desync_frames_bucket_total{bucket="gt_10"} 10476
telemt_pool_swap_total 96
telemt_pool_force_close_total 3236
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 728
telemt_me_draining_writers_reap_progress_total 29164
telemt_me_writer_removed_unexpected_total 1887
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3960
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26818
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 513
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25928
telemt_me_writer_teardown_success_total{mode="normal"} 30778
telemt_me_writer_teardown_noop_total 29190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.106733
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 728
telemt_me_refill_failed_total 3781
telemt_me_writer_restored_same_endpoint_total 1416
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14670
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 16250202
telemt_user_connections_current{user="hello"} 2406
telemt_user_octets_from_client{user="hello"} 174971766554 (162.96 GB)
telemt_user_octets_to_client{user="hello"} 1069070880998 (995.65 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1068
telemt_user_unique_ips_recent_window{user="hello"} 306
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 94220.1 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5726294
telemt_connections_bad_total 535096
telemt_connections_current 1463
telemt_connections_me_current 1463
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118468
telemt_upstream_connect_attempt_total 51796
telemt_upstream_connect_success_total 51227
telemt_upstream_connect_fail_total 483
telemt_upstream_connect_attempts_per_request{bucket="1"} 51710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 483
telemt_me_reconnect_attempts_total 30703
telemt_me_reconnect_success_total 1392
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 2338437
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4463493
telemt_me_endpoint_quarantine_total 594
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 705
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
telemt_me_writers_active_current 64
telemt_desync_total 22534
telemt_desync_full_logged_total 7847
telemt_desync_suppressed_total 14687
telemt_desync_frames_bucket_total{bucket="1_2"} 4290
telemt_desync_frames_bucket_total{bucket="3_10"} 8748
telemt_desync_frames_bucket_total{bucket="gt_10"} 9496
telemt_pool_swap_total 96
telemt_pool_force_close_total 2812
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 31881
telemt_me_writer_removed_unexpected_total 1281
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3269
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29908
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2444
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29069
telemt_me_writer_teardown_success_total{mode="normal"} 33177
telemt_me_writer_teardown_noop_total 31882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65059
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.652739
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65059
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 1804
telemt_me_writer_restored_same_endpoint_total 1158
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 3633
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 4456514
telemt_user_connections_current{user="hello"} 1463
telemt_user_octets_from_client{user="hello"} 119748487048 (111.52 GB)
telemt_user_octets_to_client{user="hello"} 1813063047162 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 31055.9 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3580113
telemt_connections_bad_total 126450
telemt_connections_current 1789
telemt_connections_me_current 1789
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1508978
telemt_upstream_connect_attempt_total 15912
telemt_upstream_connect_success_total 15784
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 15906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 31206
telemt_me_reconnect_success_total 614
telemt_me_reader_eof_total 378
telemt_me_idle_close_by_peer_total 378
telemt_me_route_drop_no_conn_total 979152
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1714084
telemt_me_endpoint_quarantine_total 195
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 234
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 93
telemt_me_floor_cap_block_total 13
telemt_me_floor_swap_idle_failed_total 13
telemt_desync_total 9533
telemt_desync_full_logged_total 3213
telemt_desync_suppressed_total 6320
telemt_desync_frames_bucket_total{bucket="1_2"} 1691
telemt_desync_frames_bucket_total{bucket="3_10"} 3646
telemt_desync_frames_bucket_total{bucket="gt_10"} 4196
telemt_pool_swap_total 33
telemt_pool_force_close_total 1080
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 9508
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 991
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8965
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 931
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8428
telemt_me_writer_teardown_success_total{mode="normal"} 9956
telemt_me_writer_teardown_noop_total 9509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19465
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.737385
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19465
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 1776
telemt_me_writer_restored_same_endpoint_total 536
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 160
telemt_me_async_recovery_trigger_total 3121
telemt_user_connections_total{user="hello"} 1714012
telemt_user_connections_current{user="hello"} 1789
telemt_user_octets_from_client{user="hello"} 49536212740 (46.13 GB)
telemt_user_octets_to_client{user="hello"} 737542844362 (686.89 GB)
telemt_user_msgs_from_client{user="hello"} 43112
telemt_user_msgs_to_client{user="hello"} 113951
telemt_user_unique_ips_current{user="hello"} 851
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 12026.5 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137705
telemt_connections_bad_total 1354
telemt_connections_current 394
telemt_connections_me_current 394
telemt_handshake_timeouts_total 3433
telemt_upstream_connect_attempt_total 5306
telemt_upstream_connect_success_total 5290
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 113
telemt_me_reconnect_success_total 65
telemt_me_reader_eof_total 68
telemt_me_idle_close_by_peer_total 68
telemt_me_route_drop_no_conn_total 39341
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119629
telemt_me_endpoint_quarantine_total 100
telemt_me_single_endpoint_shadow_rotate_total 109
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
telemt_desync_total 945
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 13
telemt_pool_force_close_total 321
telemt_me_writer_close_signal_drop_total 15
telemt_me_draining_writers_reap_progress_total 4701
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 308
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4461
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4380
telemt_me_writer_teardown_success_total{mode="normal"} 4769
telemt_me_writer_teardown_noop_total 4701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9470
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.618708
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9470
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 15
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 119450
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 2281320912 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 73034386864 (68.02 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 94224.4 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6848377
telemt_connections_bad_total 693878
telemt_connections_current 2202
telemt_connections_me_current 2202
telemt_handshake_timeouts_total 195158
telemt_upstream_connect_attempt_total 35740
telemt_upstream_connect_success_total 35598
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 35703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_reconnect_attempts_total 1448
telemt_me_reconnect_success_total 751
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 2074335
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5215772
telemt_me_endpoint_quarantine_total 626
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 721
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 19998
telemt_desync_full_logged_total 6692
telemt_desync_suppressed_total 13306
telemt_desync_frames_bucket_total{bucket="1_2"} 4862
telemt_desync_frames_bucket_total{bucket="3_10"} 7284
telemt_desync_frames_bucket_total{bucket="gt_10"} 7852
telemt_pool_swap_total 104
telemt_pool_force_close_total 2850
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 32113
telemt_me_writer_removed_unexpected_total 707
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2615
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30218
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2762
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29263
telemt_me_writer_teardown_success_total{mode="normal"} 32833
telemt_me_writer_teardown_noop_total 32115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64948
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.465629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64948
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 673
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 5191176
telemt_user_connections_current{user="hello"} 2202
telemt_user_octets_from_client{user="hello"} 104540237968 (97.36 GB)
telemt_user_octets_to_client{user="hello"} 2441837213028 (2.22 TB)
telemt_user_unique_ips_current{user="hello"} 906
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 94221.4 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5852357
telemt_connections_bad_total 556337
telemt_connections_current 1926
telemt_connections_me_current 1926
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 164420
telemt_upstream_connect_attempt_total 51853
telemt_upstream_connect_success_total 51459
telemt_upstream_connect_fail_total 335
telemt_upstream_connect_attempts_per_request{bucket="1"} 51794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 335
telemt_me_reconnect_attempts_total 5233
telemt_me_reconnect_success_total 1056
telemt_me_reader_eof_total 932
telemt_me_idle_close_by_peer_total 932
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 2126422
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4584933
telemt_me_endpoint_quarantine_total 734
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 716
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
telemt_me_writers_active_current 45
telemt_desync_total 18782
telemt_desync_full_logged_total 6333
telemt_desync_suppressed_total 12449
telemt_desync_frames_bucket_total{bucket="1_2"} 4658
telemt_desync_frames_bucket_total{bucket="3_10"} 6853
telemt_desync_frames_bucket_total{bucket="gt_10"} 7271
telemt_pool_swap_total 102
telemt_pool_force_close_total 2807
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 31040
telemt_me_writer_removed_unexpected_total 943
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3098
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28928
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2584
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28233
telemt_me_writer_teardown_success_total{mode="normal"} 32026
telemt_me_writer_teardown_noop_total 31044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.552156
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 818
telemt_me_writer_restored_fallback_total 50
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4588412
telemt_user_connections_current{user="hello"} 1926
telemt_user_octets_from_client{user="hello"} 87740158421 (81.71 GB)
telemt_user_octets_to_client{user="hello"} 1971819951428 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 842
telemt_user_unique_ips_recent_window{user="hello"} 171
```