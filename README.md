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

# Server Metrics 2026-03-22 08:33:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 41233.0 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975605
telemt_connections_bad_total 56564
telemt_connections_current 1570
telemt_connections_me_current 1570
telemt_handshake_timeouts_total 45388
telemt_upstream_connect_attempt_total 16404
telemt_upstream_connect_success_total 16403
telemt_upstream_connect_attempts_per_request{bucket="1"} 16403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 479
telemt_me_reconnect_success_total 253
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 549149
telemt_me_route_drop_channel_closed_total 176
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 811634
telemt_me_endpoint_quarantine_total 295
telemt_me_single_endpoint_shadow_rotate_total 331
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
telemt_me_writers_active_current 43
telemt_desync_total 6067
telemt_desync_full_logged_total 1696
telemt_desync_suppressed_total 4371
telemt_desync_frames_bucket_total{bucket="1_2"} 1863
telemt_desync_frames_bucket_total{bucket="3_10"} 2277
telemt_desync_frames_bucket_total{bucket="gt_10"} 1927
telemt_pool_swap_total 45
telemt_pool_force_close_total 1268
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 143
telemt_me_draining_writers_reap_progress_total 14903
telemt_me_writer_removed_unexpected_total 248
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1033
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14069
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13635
telemt_me_writer_teardown_success_total{mode="normal"} 15102
telemt_me_writer_teardown_noop_total 14905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.226388
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 143
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 231
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 810118
telemt_user_connections_current{user="hello"} 1570
telemt_user_octets_from_client{user="hello"} 11169560584 (10.40 GB)
telemt_user_octets_to_client{user="hello"} 260838259104 (242.92 GB)
telemt_user_unique_ips_current{user="hello"} 606
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 54599.6 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1475127
telemt_connections_bad_total 146138
telemt_connections_current 1403
telemt_connections_me_current 1403
telemt_handshake_timeouts_total 42401
telemt_upstream_connect_attempt_total 28622
telemt_upstream_connect_success_total 28197
telemt_upstream_connect_fail_total 373
telemt_upstream_connect_attempts_per_request{bucket="1"} 28570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 373
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2463
telemt_me_reconnect_success_total 1061
telemt_me_reader_eof_total 963
telemt_me_idle_close_by_peer_total 963
telemt_me_route_drop_no_conn_total 640946
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1111119
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 434
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
telemt_desync_total 4948
telemt_desync_full_logged_total 2867
telemt_desync_suppressed_total 2081
telemt_desync_frames_bucket_total{bucket="1_2"} 1074
telemt_desync_frames_bucket_total{bucket="3_10"} 1922
telemt_desync_frames_bucket_total{bucket="gt_10"} 1952
telemt_pool_swap_total 56
telemt_pool_force_close_total 1551
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 22376
telemt_me_writer_removed_unexpected_total 933
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2198
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21100
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1427
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20825
telemt_me_writer_teardown_success_total{mode="normal"} 23298
telemt_me_writer_teardown_noop_total 22376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45674
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.064786
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45674
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1112690
telemt_user_connections_current{user="hello"} 1403
telemt_user_octets_from_client{user="hello"} 17187955126 (16.01 GB)
telemt_user_octets_to_client{user="hello"} 390167716983 (363.37 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 920
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 129459.2 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9691478
telemt_connections_bad_total 873525
telemt_connections_current 4993
telemt_connections_me_current 4993
telemt_handshake_timeouts_total 291035
telemt_upstream_connect_attempt_total 47767
telemt_upstream_connect_success_total 47687
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 47695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1897
telemt_me_reconnect_success_total 986
telemt_me_reader_eof_total 995
telemt_me_idle_close_by_peer_total 995
telemt_me_route_drop_no_conn_total 5432759
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7604444
telemt_me_endpoint_quarantine_total 810
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 972
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
telemt_me_writers_active_current 46
telemt_desync_total 32988
telemt_desync_full_logged_total 10852
telemt_desync_suppressed_total 22136
telemt_desync_frames_bucket_total{bucket="1_2"} 7235
telemt_desync_frames_bucket_total{bucket="3_10"} 12809
telemt_desync_frames_bucket_total{bucket="gt_10"} 12944
telemt_pool_swap_total 139
telemt_pool_force_close_total 4628
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 43582
telemt_me_writer_removed_unexpected_total 956
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3664
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40350
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 309
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38954
telemt_me_writer_teardown_success_total{mode="normal"} 44014
telemt_me_writer_teardown_noop_total 43626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87640
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 185.304976
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87640
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 884
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 7594713
telemt_user_connections_current{user="hello"} 4993
telemt_user_octets_from_client{user="hello"} 125517595120 (116.90 GB)
telemt_user_octets_to_client{user="hello"} 2539228389788 (2.31 TB)
telemt_user_unique_ips_current{user="hello"} 1917
telemt_user_unique_ips_recent_window{user="hello"} 766
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 129460.6 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7910733
telemt_connections_bad_total 706313
telemt_connections_current 4414
telemt_connections_me_current 4414
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 254541
telemt_upstream_connect_attempt_total 53770
telemt_upstream_connect_success_total 53295
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 53538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2825
telemt_me_reconnect_success_total 1074
telemt_me_reader_eof_total 996
telemt_me_idle_close_by_peer_total 996
telemt_me_route_drop_no_conn_total 2651766
telemt_me_route_drop_channel_closed_total 318
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5849653
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 998
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
telemt_me_writers_active_current 47
telemt_desync_total 26687
telemt_desync_full_logged_total 9148
telemt_desync_suppressed_total 17539
telemt_desync_frames_bucket_total{bucket="1_2"} 6404
telemt_desync_frames_bucket_total{bucket="3_10"} 10330
telemt_desync_frames_bucket_total{bucket="gt_10"} 9953
telemt_pool_swap_total 141
telemt_pool_force_close_total 4213
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 453
telemt_me_draining_writers_reap_progress_total 41795
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3559
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39166
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3965
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37582
telemt_me_writer_teardown_success_total{mode="normal"} 42725
telemt_me_writer_teardown_noop_total 41801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84526
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.380979
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84526
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 453
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 911
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5772287
telemt_user_connections_current{user="hello"} 4414
telemt_user_octets_from_client{user="hello"} 160318340751 (149.31 GB)
telemt_user_octets_to_client{user="hello"} 2772929134674 (2.52 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1703
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 129426.4 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7611437
telemt_connections_bad_total 631340
telemt_connections_current 3958
telemt_connections_me_current 3958
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 252118
telemt_upstream_connect_attempt_total 58190
telemt_upstream_connect_success_total 57515
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2822
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1117
telemt_me_idle_close_by_peer_total 1117
telemt_me_route_drop_no_conn_total 3057920
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5675176
telemt_me_endpoint_quarantine_total 911
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 954
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
telemt_me_writers_active_current 46
telemt_desync_total 26632
telemt_desync_full_logged_total 9057
telemt_desync_suppressed_total 17575
telemt_desync_frames_bucket_total{bucket="1_2"} 6424
telemt_desync_frames_bucket_total{bucket="3_10"} 10220
telemt_desync_frames_bucket_total{bucket="gt_10"} 9988
telemt_pool_swap_total 138
telemt_pool_force_close_total 4112
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 477
telemt_me_draining_writers_reap_progress_total 42813
telemt_me_writer_removed_unexpected_total 1128
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3808
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40117
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3802
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 310
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38701
telemt_me_writer_teardown_success_total{mode="normal"} 43925
telemt_me_writer_teardown_noop_total 42825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86750
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.149869
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86750
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 477
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1055
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 5668256
telemt_user_connections_current{user="hello"} 3958
telemt_user_octets_from_client{user="hello"} 147387187931 (137.27 GB)
telemt_user_octets_to_client{user="hello"} 2520686586863 (2.29 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1590
telemt_user_unique_ips_recent_window{user="hello"} 586
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 129464.0 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24515446
telemt_connections_bad_total 1999115
telemt_connections_current 6043
telemt_connections_me_current 6043
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 703134
telemt_upstream_connect_attempt_total 241839
telemt_upstream_connect_success_total 222069
telemt_upstream_connect_fail_total 17762
telemt_upstream_connect_attempts_per_request{bucket="1"} 239831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17762
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 68113
telemt_me_reconnect_success_total 2746
telemt_me_reader_eof_total 1695
telemt_me_idle_close_by_peer_total 1693
telemt_me_route_drop_no_conn_total 47726700
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19843943
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 1002
telemt_me_single_endpoint_outage_enter_total 165
telemt_me_single_endpoint_outage_exit_total 165
telemt_me_single_endpoint_outage_reconnect_attempt_total 336
telemt_me_single_endpoint_outage_reconnect_success_total 87
telemt_me_single_endpoint_quarantine_bypass_total 336
telemt_me_single_endpoint_shadow_rotate_total 1015
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 73
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
telemt_me_writers_active_current 74
telemt_desync_total 38650
telemt_desync_full_logged_total 11377
telemt_desync_suppressed_total 27273
telemt_desync_frames_bucket_total{bucket="1_2"} 8590
telemt_desync_frames_bucket_total{bucket="3_10"} 17045
telemt_desync_frames_bucket_total{bucket="gt_10"} 13015
telemt_pool_swap_total 134
telemt_pool_force_close_total 4256
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 977
telemt_me_draining_writers_reap_progress_total 40247
telemt_me_writer_removed_unexpected_total 2517
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5442
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37047
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3653
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 603
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35991
telemt_me_writer_teardown_success_total{mode="normal"} 42489
telemt_me_writer_teardown_noop_total 40279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82768
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.940653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82768
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 977
telemt_me_refill_failed_total 3959
telemt_me_writer_restored_same_endpoint_total 1870
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 677
telemt_me_async_recovery_trigger_total 14906
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 20009281
telemt_user_connections_current{user="hello"} 6043
telemt_user_octets_from_client{user="hello"} 279948645383 (260.72 GB)
telemt_user_octets_to_client{user="hello"} 1450387230967 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2135
telemt_user_unique_ips_recent_window{user="hello"} 1080
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 129431.6 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7243843
telemt_connections_bad_total 656013
telemt_connections_current 4427
telemt_connections_me_current 4427
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 148591
telemt_upstream_connect_attempt_total 66619
telemt_upstream_connect_success_total 65833
telemt_upstream_connect_fail_total 669
telemt_upstream_connect_attempts_per_request{bucket="1"} 66502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27944
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 669
telemt_me_reconnect_attempts_total 70263
telemt_me_reconnect_success_total 1989
telemt_me_reader_eof_total 1750
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 2835763
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5690890
telemt_me_endpoint_quarantine_total 868
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 980
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
telemt_me_writers_active_current 44
telemt_desync_total 28686
telemt_desync_full_logged_total 9974
telemt_desync_suppressed_total 18712
telemt_desync_frames_bucket_total{bucket="1_2"} 5722
telemt_desync_frames_bucket_total{bucket="3_10"} 11050
telemt_desync_frames_bucket_total{bucket="gt_10"} 11914
telemt_pool_swap_total 135
telemt_pool_force_close_total 3895
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 461
telemt_me_draining_writers_reap_progress_total 44963
telemt_me_writer_removed_unexpected_total 1780
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4522
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42247
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 433
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41068
telemt_me_writer_teardown_success_total{mode="normal"} 46769
telemt_me_writer_teardown_noop_total 44964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91733
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.358625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91733
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 461
telemt_me_refill_failed_total 4226
telemt_me_writer_restored_same_endpoint_total 1651
telemt_me_writer_restored_fallback_total 40
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 5681404
telemt_user_connections_current{user="hello"} 4427
telemt_user_octets_from_client{user="hello"} 143106837180 (133.28 GB)
telemt_user_octets_to_client{user="hello"} 2357608532534 (2.14 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1782
telemt_user_unique_ips_recent_window{user="hello"} 631
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 66267.5 (18h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5673748
telemt_connections_bad_total 222952
telemt_connections_current 3738
telemt_connections_me_current 3738
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2255170
telemt_upstream_connect_attempt_total 35751
telemt_upstream_connect_success_total 35501
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 35744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_reconnect_attempts_total 47367
telemt_me_reconnect_success_total 1175
telemt_me_reader_eof_total 846
telemt_me_idle_close_by_peer_total 846
telemt_me_route_drop_no_conn_total 1418057
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2842910
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 507
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
telemt_me_writers_active_current 52
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 15406
telemt_desync_full_logged_total 5244
telemt_desync_suppressed_total 10162
telemt_desync_frames_bucket_total{bucket="1_2"} 3024
telemt_desync_frames_bucket_total{bucket="3_10"} 5917
telemt_desync_frames_bucket_total{bucket="gt_10"} 6465
telemt_pool_swap_total 71
telemt_pool_force_close_total 2124
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 199
telemt_me_draining_writers_reap_progress_total 23906
telemt_me_writer_removed_unexpected_total 916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22786
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1852
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 272
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21782
telemt_me_writer_teardown_success_total{mode="normal"} 24844
telemt_me_writer_teardown_noop_total 23912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48756
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.525870
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48756
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 199
telemt_me_refill_failed_total 2687
telemt_me_writer_restored_same_endpoint_total 1048
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 2844084
telemt_user_connections_current{user="hello"} 3738
telemt_user_octets_from_client{user="hello"} 72961357116 (67.95 GB)
telemt_user_octets_to_client{user="hello"} 1246632512910 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1577
telemt_user_unique_ips_recent_window{user="hello"} 648
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 47238.2 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410565
telemt_connections_bad_total 2881
telemt_connections_current 972
telemt_connections_me_current 972
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8280
telemt_upstream_connect_attempt_total 25181
telemt_upstream_connect_success_total 25122
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 25176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 1007
telemt_me_reconnect_success_total 383
telemt_me_reader_eof_total 377
telemt_me_idle_close_by_peer_total 377
telemt_me_route_drop_no_conn_total 129008
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370766
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 408
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
telemt_me_writers_active_current 91
telemt_desync_total 1694
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 1198
telemt_desync_frames_bucket_total{bucket="1_2"} 504
telemt_desync_frames_bucket_total{bucket="3_10"} 667
telemt_desync_frames_bucket_total{bucket="gt_10"} 523
telemt_pool_swap_total 51
telemt_pool_force_close_total 1142
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 20155
telemt_me_writer_removed_unexpected_total 362
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19109
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19013
telemt_me_writer_teardown_success_total{mode="normal"} 20532
telemt_me_writer_teardown_noop_total 20155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40687
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.832615
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40687
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 332
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 372962
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 7189046685 (6.70 GB)
telemt_user_octets_to_client{user="hello"} 193117119203 (179.85 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 129435.9 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8918854
telemt_connections_bad_total 1023526
telemt_connections_current 5189
telemt_connections_me_current 5189
telemt_handshake_timeouts_total 246729
telemt_upstream_connect_attempt_total 50365
telemt_upstream_connect_success_total 50174
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 50321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 1894
telemt_me_reconnect_success_total 1027
telemt_me_reader_eof_total 998
telemt_me_idle_close_by_peer_total 998
telemt_me_route_drop_no_conn_total 2494811
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6607460
telemt_me_endpoint_quarantine_total 918
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 983
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
telemt_me_writers_active_current 45
telemt_desync_total 26499
telemt_desync_full_logged_total 8697
telemt_desync_suppressed_total 17802
telemt_desync_frames_bucket_total{bucket="1_2"} 6536
telemt_desync_frames_bucket_total{bucket="3_10"} 9661
telemt_desync_frames_bucket_total{bucket="gt_10"} 10302
telemt_pool_swap_total 143
telemt_pool_force_close_total 3840
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 465
telemt_me_draining_writers_reap_progress_total 45450
telemt_me_writer_removed_unexpected_total 959
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3618
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42820
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3741
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 99
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41610
telemt_me_writer_teardown_success_total{mode="normal"} 46438
telemt_me_writer_teardown_noop_total 45452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91890
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.868039
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91890
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 465
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6580553
telemt_user_connections_current{user="hello"} 5189
telemt_user_octets_from_client{user="hello"} 128744741632 (119.90 GB)
telemt_user_octets_to_client{user="hello"} 3094582681356 (2.81 TB)
telemt_user_unique_ips_current{user="hello"} 1877
telemt_user_unique_ips_recent_window{user="hello"} 707
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 129432.6 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7754975
telemt_connections_bad_total 859409
telemt_connections_current 4330
telemt_connections_me_current 4330
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 207090
telemt_upstream_connect_attempt_total 66397
telemt_upstream_connect_success_total 65885
telemt_upstream_connect_fail_total 446
telemt_upstream_connect_attempts_per_request{bucket="1"} 66331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 630
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 446
telemt_me_reconnect_attempts_total 6378
telemt_me_reconnect_success_total 1447
telemt_me_reader_eof_total 1298
telemt_me_idle_close_by_peer_total 1298
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2628809
telemt_me_route_drop_channel_closed_total 226
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5899820
telemt_me_endpoint_quarantine_total 1010
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 980
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
telemt_desync_total 25400
telemt_desync_full_logged_total 8449
telemt_desync_suppressed_total 16951
telemt_desync_frames_bucket_total{bucket="1_2"} 6256
telemt_desync_frames_bucket_total{bucket="3_10"} 9341
telemt_desync_frames_bucket_total{bucket="gt_10"} 9803
telemt_pool_swap_total 140
telemt_pool_force_close_total 3786
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 461
telemt_me_draining_writers_reap_progress_total 44090
telemt_me_writer_removed_unexpected_total 1313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41249
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3517
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 269
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40304
telemt_me_writer_teardown_success_total{mode="normal"} 45465
telemt_me_writer_teardown_noop_total 44094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89559
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.802229
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89559
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 461
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 1131
telemt_me_writer_restored_fallback_total 84
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5900827
telemt_user_connections_current{user="hello"} 4330
telemt_user_octets_from_client{user="hello"} 108589786361 (101.13 GB)
telemt_user_octets_to_client{user="hello"} 2549893738004 (2.32 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1684
telemt_user_unique_ips_recent_window{user="hello"} 622
```