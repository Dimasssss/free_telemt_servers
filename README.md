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

# Server Metrics 2026-03-22 09:39:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 45207.7 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1147039
telemt_connections_bad_total 62293
telemt_connections_current 1646
telemt_connections_me_current 1646
telemt_handshake_timeouts_total 52596
telemt_upstream_connect_attempt_total 17707
telemt_upstream_connect_success_total 17706
telemt_upstream_connect_attempts_per_request{bucket="1"} 17706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 537
telemt_me_reconnect_success_total 270
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 270
telemt_me_route_drop_no_conn_total 617030
telemt_me_route_drop_channel_closed_total 251
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954755
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 319
telemt_me_single_endpoint_shadow_rotate_total 365
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
telemt_desync_total 6743
telemt_desync_full_logged_total 1944
telemt_desync_suppressed_total 4799
telemt_desync_frames_bucket_total{bucket="1_2"} 1991
telemt_desync_frames_bucket_total{bucket="3_10"} 2541
telemt_desync_frames_bucket_total{bucket="gt_10"} 2211
telemt_pool_swap_total 50
telemt_pool_force_close_total 1437
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 16109
telemt_me_writer_removed_unexpected_total 266
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1118
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15196
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14672
telemt_me_writer_teardown_success_total{mode="normal"} 16314
telemt_me_writer_teardown_noop_total 16111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32425
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 66.974983
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32425
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 246
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 952998
telemt_user_connections_current{user="hello"} 1646
telemt_user_octets_from_client{user="hello"} 14953142912 (13.93 GB)
telemt_user_octets_to_client{user="hello"} 305127094192 (284.17 GB)
telemt_user_unique_ips_current{user="hello"} 576
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 58574.0 (16h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1725838
telemt_connections_bad_total 159134
telemt_connections_current 3053
telemt_connections_me_current 3053
telemt_handshake_timeouts_total 45984
telemt_upstream_connect_attempt_total 34936
telemt_upstream_connect_success_total 34487
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 34881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2627
telemt_me_reconnect_success_total 1147
telemt_me_reader_eof_total 1043
telemt_me_idle_close_by_peer_total 1043
telemt_me_route_drop_no_conn_total 942658
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1319599
telemt_me_endpoint_quarantine_total 505
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 462
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
telemt_me_writers_active_current 86
telemt_me_writers_warm_current 18
telemt_desync_total 5886
telemt_desync_full_logged_total 3382
telemt_desync_suppressed_total 2504
telemt_desync_frames_bucket_total{bucket="1_2"} 1312
telemt_desync_frames_bucket_total{bucket="3_10"} 2309
telemt_desync_frames_bucket_total{bucket="gt_10"} 2265
telemt_pool_swap_total 59
telemt_pool_force_close_total 1610
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 23778
telemt_me_writer_removed_unexpected_total 1011
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2366
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22414
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22168
telemt_me_writer_teardown_success_total{mode="normal"} 24780
telemt_me_writer_teardown_noop_total 23778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48558
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.313764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48558
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 928
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1325748
telemt_user_connections_current{user="hello"} 3052
telemt_user_octets_from_client{user="hello"} 19315919830 (17.99 GB)
telemt_user_octets_to_client{user="hello"} 421516953504 (392.57 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1730
telemt_user_unique_ips_recent_window{user="hello"} 813
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 133434.2 (37h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10437078
telemt_connections_bad_total 925822
telemt_connections_current 4269
telemt_connections_me_current 4269
telemt_handshake_timeouts_total 301261
telemt_upstream_connect_attempt_total 49033
telemt_upstream_connect_success_total 48953
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2055
telemt_me_reconnect_success_total 1053
telemt_me_reader_eof_total 1046
telemt_me_idle_close_by_peer_total 1045
telemt_me_route_drop_no_conn_total 6473446
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8228503
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 996
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
telemt_desync_total 35373
telemt_desync_full_logged_total 11529
telemt_desync_suppressed_total 23844
telemt_desync_frames_bucket_total{bucket="1_2"} 7876
telemt_desync_frames_bucket_total{bucket="3_10"} 13744
telemt_desync_frames_bucket_total{bucket="gt_10"} 13753
telemt_pool_swap_total 144
telemt_pool_force_close_total 4820
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 738
telemt_me_draining_writers_reap_progress_total 44735
telemt_me_writer_removed_unexpected_total 1004
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3797
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41392
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 323
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39915
telemt_me_writer_teardown_success_total{mode="normal"} 45189
telemt_me_writer_teardown_noop_total 44779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 200.453237
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 738
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 925
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 8218208
telemt_user_connections_current{user="hello"} 4269
telemt_user_octets_from_client{user="hello"} 132193362856 (123.11 GB)
telemt_user_octets_to_client{user="hello"} 2633543515564 (2.40 TB)
telemt_user_unique_ips_current{user="hello"} 1510
telemt_user_unique_ips_recent_window{user="hello"} 1356
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 133435.4 (37h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8382717
telemt_connections_bad_total 754284
telemt_connections_current 3543
telemt_connections_me_current 3543
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 265549
telemt_upstream_connect_attempt_total 55217
telemt_upstream_connect_success_total 54723
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 54973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3005
telemt_me_reconnect_success_total 1172
telemt_me_reader_eof_total 1079
telemt_me_idle_close_by_peer_total 1079
telemt_me_route_drop_no_conn_total 2906826
telemt_me_route_drop_channel_closed_total 343
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6207276
telemt_me_endpoint_quarantine_total 849
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1028
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
telemt_me_writers_active_current 47
telemt_desync_total 28390
telemt_desync_full_logged_total 9653
telemt_desync_suppressed_total 18737
telemt_desync_frames_bucket_total{bucket="1_2"} 6866
telemt_desync_frames_bucket_total{bucket="3_10"} 10984
telemt_desync_frames_bucket_total{bucket="gt_10"} 10540
telemt_pool_swap_total 145
telemt_pool_force_close_total 4395
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 43083
telemt_me_writer_removed_unexpected_total 1096
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3726
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40347
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 297
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38688
telemt_me_writer_teardown_success_total{mode="normal"} 44073
telemt_me_writer_teardown_noop_total 43089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87162
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.866024
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87162
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 995
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6129458
telemt_user_connections_current{user="hello"} 3543
telemt_user_octets_from_client{user="hello"} 165584784371 (154.21 GB)
telemt_user_octets_to_client{user="hello"} 2913522172818 (2.65 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1370
telemt_user_unique_ips_recent_window{user="hello"} 850
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 133399.4 (37h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8047702
telemt_connections_bad_total 675307
telemt_connections_current 4834
telemt_connections_me_current 4834
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 263741
telemt_upstream_connect_attempt_total 59772
telemt_upstream_connect_success_total 59080
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3411
telemt_me_reconnect_success_total 1453
telemt_me_reader_eof_total 1342
telemt_me_idle_close_by_peer_total 1342
telemt_me_route_drop_no_conn_total 3331786
telemt_me_route_drop_channel_closed_total 215
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6005335
telemt_me_endpoint_quarantine_total 922
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 978
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
telemt_me_writers_active_current 44
telemt_desync_total 28085
telemt_desync_full_logged_total 9552
telemt_desync_suppressed_total 18533
telemt_desync_frames_bucket_total{bucket="1_2"} 6778
telemt_desync_frames_bucket_total{bucket="3_10"} 10790
telemt_desync_frames_bucket_total{bucket="gt_10"} 10517
telemt_pool_swap_total 141
telemt_pool_force_close_total 4237
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 500
telemt_me_draining_writers_reap_progress_total 43972
telemt_me_writer_removed_unexpected_total 1368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4119
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41193
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3858
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39735
telemt_me_writer_teardown_success_total{mode="normal"} 45312
telemt_me_writer_teardown_noop_total 43984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.153418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 500
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1279
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 5997937
telemt_user_connections_current{user="hello"} 4834
telemt_user_octets_from_client{user="hello"} 152130691607 (141.68 GB)
telemt_user_octets_to_client{user="hello"} 2637093027859 (2.40 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1985
telemt_user_unique_ips_recent_window{user="hello"} 662
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 3679.4 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1513069
telemt_connections_bad_total 120842
telemt_connections_current 6460
telemt_connections_me_current 6460
telemt_handshake_timeouts_total 18722
telemt_upstream_connect_attempt_total 8004
telemt_upstream_connect_success_total 7588
telemt_upstream_connect_fail_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 7926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2668
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 338
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 314
telemt_me_reconnect_success_total 112
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 3280708
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1247345
telemt_me_endpoint_quarantine_total 18
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 34
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
telemt_me_writers_warm_current 30
telemt_desync_total 2014
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 1498
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 2
telemt_pool_force_close_total 95
telemt_me_writer_close_signal_drop_total 45
telemt_me_draining_writers_reap_progress_total 926
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 867
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 44
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 831
telemt_me_writer_teardown_success_total{mode="normal"} 1031
telemt_me_writer_teardown_noop_total 926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1957
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.038062
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1957
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 45
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 67
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1253408
telemt_user_connections_current{user="hello"} 6460
telemt_user_octets_from_client{user="hello"} 7422072166 (6.91 GB)
telemt_user_octets_to_client{user="hello"} 38071142279 (35.46 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2321
telemt_user_unique_ips_recent_window{user="hello"} 1357
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 133406.2 (37h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7667839
telemt_connections_bad_total 681242
telemt_connections_current 3802
telemt_connections_me_current 3802
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 157777
telemt_upstream_connect_attempt_total 75888
telemt_upstream_connect_success_total 75062
telemt_upstream_connect_fail_total 706
telemt_upstream_connect_attempts_per_request{bucket="1"} 75768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 443
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 706
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70461
telemt_me_reconnect_success_total 2079
telemt_me_reader_eof_total 1824
telemt_me_idle_close_by_peer_total 1823
telemt_me_route_drop_no_conn_total 3108702
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6037037
telemt_me_endpoint_quarantine_total 896
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1006
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
telemt_desync_total 30552
telemt_desync_full_logged_total 10571
telemt_desync_suppressed_total 19981
telemt_desync_frames_bucket_total{bucket="1_2"} 6155
telemt_desync_frames_bucket_total{bucket="3_10"} 11734
telemt_desync_frames_bucket_total{bucket="gt_10"} 12663
telemt_pool_swap_total 139
telemt_pool_force_close_total 4031
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 483
telemt_me_draining_writers_reap_progress_total 46240
telemt_me_writer_removed_unexpected_total 1853
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4713
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43407
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3544
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 487
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42209
telemt_me_writer_teardown_success_total{mode="normal"} 48120
telemt_me_writer_teardown_noop_total 46241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94361
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.697412
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94361
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 483
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 1725
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 6034741
telemt_user_connections_current{user="hello"} 3802
telemt_user_octets_from_client{user="hello"} 150231305667 (139.91 GB)
telemt_user_octets_to_client{user="hello"} 2462087819171 (2.24 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1333
telemt_user_unique_ips_recent_window{user="hello"} 1234
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 70242.3 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6370812
telemt_connections_bad_total 246524
telemt_connections_current 5169
telemt_connections_me_current 5169
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2576312
telemt_upstream_connect_attempt_total 37229
telemt_upstream_connect_success_total 36968
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 37222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_reconnect_attempts_total 47474
telemt_me_reconnect_success_total 1250
telemt_me_reader_eof_total 915
telemt_me_idle_close_by_peer_total 915
telemt_me_route_drop_no_conn_total 1690442
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3169517
telemt_me_endpoint_quarantine_total 481
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 10
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 17316
telemt_desync_full_logged_total 5837
telemt_desync_suppressed_total 11479
telemt_desync_frames_bucket_total{bucket="1_2"} 3453
telemt_desync_frames_bucket_total{bucket="3_10"} 6626
telemt_desync_frames_bucket_total{bucket="gt_10"} 7237
telemt_pool_swap_total 74
telemt_pool_force_close_total 2246
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 216
telemt_me_draining_writers_reap_progress_total 25204
telemt_me_writer_removed_unexpected_total 986
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2198
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24014
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1931
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 315
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22958
telemt_me_writer_teardown_success_total{mode="normal"} 26212
telemt_me_writer_teardown_noop_total 25210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51422
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.758997
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51422
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 216
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 1117
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3170078
telemt_user_connections_current{user="hello"} 5169
telemt_user_octets_from_client{user="hello"} 78788043088 (73.38 GB)
telemt_user_octets_to_client{user="hello"} 1352507117774 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2060
telemt_user_unique_ips_recent_window{user="hello"} 989
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 51213.1 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487451
telemt_connections_bad_total 3695
telemt_connections_current 982
telemt_connections_me_current 982
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9134
telemt_upstream_connect_attempt_total 27130
telemt_upstream_connect_success_total 27067
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 271
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1127
telemt_me_reconnect_success_total 451
telemt_me_reader_eof_total 450
telemt_me_idle_close_by_peer_total 450
telemt_me_route_drop_no_conn_total 158864
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439996
telemt_me_endpoint_quarantine_total 475
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 437
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
telemt_me_writers_active_current 44
telemt_desync_total 2080
telemt_desync_full_logged_total 616
telemt_desync_suppressed_total 1464
telemt_desync_frames_bucket_total{bucket="1_2"} 611
telemt_desync_frames_bucket_total{bucket="3_10"} 807
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 54
telemt_pool_force_close_total 1271
telemt_me_writer_close_signal_drop_total 55
telemt_me_draining_writers_reap_progress_total 21903
telemt_me_writer_removed_unexpected_total 433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20753
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1220
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20632
telemt_me_writer_teardown_success_total{mode="normal"} 22353
telemt_me_writer_teardown_noop_total 21903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44256
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.105697
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44256
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 55
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 399
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 442080
telemt_user_connections_current{user="hello"} 982
telemt_user_octets_from_client{user="hello"} 8899297101 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 218698346143 (203.68 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 133410.7 (37h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9426467
telemt_connections_bad_total 1098014
telemt_connections_current 5088
telemt_connections_me_current 5088
telemt_handshake_timeouts_total 256904
telemt_upstream_connect_attempt_total 51555
telemt_upstream_connect_success_total 51357
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 51509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25915
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 1922
telemt_me_reconnect_success_total 1050
telemt_me_reader_eof_total 1022
telemt_me_idle_close_by_peer_total 1022
telemt_me_route_drop_no_conn_total 2670527
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6995646
telemt_me_endpoint_quarantine_total 944
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1012
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
telemt_desync_total 28289
telemt_desync_full_logged_total 9273
telemt_desync_suppressed_total 19016
telemt_desync_frames_bucket_total{bucket="1_2"} 6987
telemt_desync_frames_bucket_total{bucket="3_10"} 10312
telemt_desync_frames_bucket_total{bucket="gt_10"} 10990
telemt_pool_swap_total 148
telemt_pool_force_close_total 3993
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 486
telemt_me_draining_writers_reap_progress_total 46509
telemt_me_writer_removed_unexpected_total 982
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3736
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43786
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3885
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42516
telemt_me_writer_teardown_success_total{mode="normal"} 47522
telemt_me_writer_teardown_noop_total 46511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94033
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.918747
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94033
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 486
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 921
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 6968180
telemt_user_connections_current{user="hello"} 5088
telemt_user_octets_from_client{user="hello"} 135386049392 (126.09 GB)
telemt_user_octets_to_client{user="hello"} 3262364048784 (2.97 TB)
telemt_user_unique_ips_current{user="hello"} 1716
telemt_user_unique_ips_recent_window{user="hello"} 1443
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 133407.2 (37h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8191745
telemt_connections_bad_total 913494
telemt_connections_current 4418
telemt_connections_me_current 4418
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 214797
telemt_upstream_connect_attempt_total 76031
telemt_upstream_connect_success_total 75494
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 75962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1966
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_reconnect_attempts_total 6498
telemt_me_reconnect_success_total 1514
telemt_me_reader_eof_total 1345
telemt_me_idle_close_by_peer_total 1345
telemt_me_seq_mismatch_total 63
telemt_me_route_drop_no_conn_total 2870364
telemt_me_route_drop_channel_closed_total 245
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6243389
telemt_me_endpoint_quarantine_total 1044
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1012
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
telemt_desync_total 27219
telemt_desync_full_logged_total 9030
telemt_desync_suppressed_total 18189
telemt_desync_frames_bucket_total{bucket="1_2"} 6697
telemt_desync_frames_bucket_total{bucket="3_10"} 10012
telemt_desync_frames_bucket_total{bucket="gt_10"} 10510
telemt_pool_swap_total 145
telemt_pool_force_close_total 3920
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 45185
telemt_me_writer_removed_unexpected_total 1362
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42227
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3633
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 287
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41265
telemt_me_writer_teardown_success_total{mode="normal"} 46609
telemt_me_writer_teardown_noop_total 45189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91798
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.422980
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91798
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 287
telemt_me_writer_restored_same_endpoint_total 1183
telemt_me_writer_restored_fallback_total 87
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 6251943
telemt_user_connections_current{user="hello"} 4418
telemt_user_octets_from_client{user="hello"} 114289944357 (106.44 GB)
telemt_user_octets_to_client{user="hello"} 2662521065691 (2.42 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1685
telemt_user_unique_ips_recent_window{user="hello"} 1352
```