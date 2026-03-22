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

# Server Metrics 2026-03-22 17:25:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 73150.8 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2641684
telemt_connections_bad_total 143015
telemt_connections_current 1443
telemt_connections_me_current 1443
telemt_handshake_timeouts_total 91111
telemt_upstream_connect_attempt_total 26962
telemt_upstream_connect_success_total 26961
telemt_upstream_connect_attempts_per_request{bucket="1"} 26961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1090
telemt_me_reconnect_success_total 463
telemt_me_reader_eof_total 466
telemt_me_idle_close_by_peer_total 466
telemt_me_route_drop_no_conn_total 2197977
telemt_me_route_drop_channel_closed_total 899
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2254532
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 503
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 571
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
telemt_me_writers_active_current 43
telemt_desync_total 10476
telemt_desync_full_logged_total 3318
telemt_desync_suppressed_total 7158
telemt_desync_frames_bucket_total{bucket="1_2"} 2805
telemt_desync_frames_bucket_total{bucket="3_10"} 3902
telemt_desync_frames_bucket_total{bucket="gt_10"} 3769
telemt_pool_swap_total 81
telemt_pool_force_close_total 2515
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 509
telemt_me_draining_writers_reap_progress_total 24638
telemt_me_writer_removed_unexpected_total 452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1809
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23052
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2463
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22123
telemt_me_writer_teardown_success_total{mode="normal"} 24861
telemt_me_writer_teardown_noop_total 24648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49509
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 242.874514
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49509
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 509
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2250794
telemt_user_connections_current{user="hello"} 1443
telemt_user_octets_from_client{user="hello"} 33205632256 (30.93 GB)
telemt_user_octets_to_client{user="hello"} 593550231016 (552.79 GB)
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 86516.8 (24h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3668564
telemt_connections_bad_total 332647
telemt_connections_current 1182
telemt_connections_me_current 1182
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 92092
telemt_upstream_connect_attempt_total 53680
telemt_upstream_connect_success_total 53009
telemt_upstream_connect_fail_total 591
telemt_upstream_connect_attempts_per_request{bucket="1"} 53600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 591
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6213
telemt_me_reconnect_success_total 2257
telemt_me_reader_eof_total 2185
telemt_me_idle_close_by_peer_total 2185
telemt_me_route_drop_no_conn_total 3551916
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2909990
telemt_me_endpoint_quarantine_total 687
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 666
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
telemt_me_writers_warm_current 42
telemt_desync_total 11449
telemt_desync_full_logged_total 6393
telemt_desync_suppressed_total 5056
telemt_desync_frames_bucket_total{bucket="1_2"} 2671
telemt_desync_frames_bucket_total{bucket="3_10"} 4489
telemt_desync_frames_bucket_total{bucket="gt_10"} 4289
telemt_pool_swap_total 82
telemt_pool_force_close_total 2430
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 205
telemt_me_draining_writers_reap_progress_total 34366
telemt_me_writer_removed_unexpected_total 2138
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4110
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32402
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2070
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31936
telemt_me_writer_teardown_success_total{mode="normal"} 36512
telemt_me_writer_teardown_noop_total 34366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70878
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.156730
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70878
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 205
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1948
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 2921200
telemt_user_connections_current{user="hello"} 1182
telemt_user_octets_from_client{user="hello"} 37017537691 (34.48 GB)
telemt_user_octets_to_client{user="hello"} 663105577538 (617.57 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 706
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 161376.8 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15529954
telemt_connections_bad_total 1484082
telemt_connections_current 2165
telemt_connections_me_current 2165
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 379802
telemt_upstream_connect_attempt_total 72586
telemt_upstream_connect_success_total 72488
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2698
telemt_me_reconnect_success_total 1387
telemt_me_reader_eof_total 1325
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 13855117
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12379707
telemt_me_endpoint_quarantine_total 1016
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1203
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
telemt_me_writers_active_current 43
telemt_desync_total 50601
telemt_desync_full_logged_total 15901
telemt_desync_suppressed_total 34700
telemt_desync_frames_bucket_total{bucket="1_2"} 11299
telemt_desync_frames_bucket_total{bucket="3_10"} 19758
telemt_desync_frames_bucket_total{bucket="gt_10"} 19544
telemt_pool_swap_total 174
telemt_pool_force_close_total 5908
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 955
telemt_me_draining_writers_reap_progress_total 53060
telemt_me_writer_removed_unexpected_total 1279
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4648
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48982
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47152
telemt_me_writer_teardown_success_total{mode="normal"} 53630
telemt_me_writer_teardown_noop_total 53110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 303.639019
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 955
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12380698
telemt_user_connections_current{user="hello"} 2165
telemt_user_octets_from_client{user="hello"} 177854610993 (165.64 GB)
telemt_user_octets_to_client{user="hello"} 3219123473615 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 823
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 161378.3 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11193764
telemt_connections_bad_total 1089662
telemt_connections_current 1711
telemt_connections_me_current 1711
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 335851
telemt_upstream_connect_attempt_total 84818
telemt_upstream_connect_success_total 83646
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 84484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3698
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 4001
telemt_me_reconnect_success_total 1661
telemt_me_reader_eof_total 1532
telemt_me_idle_close_by_peer_total 1532
telemt_me_route_drop_no_conn_total 4398390
telemt_me_route_drop_channel_closed_total 486
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8343371
telemt_me_endpoint_quarantine_total 1017
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1220
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_me_writers_active_current 80
telemt_desync_total 37110
telemt_desync_full_logged_total 12482
telemt_desync_suppressed_total 24628
telemt_desync_frames_bucket_total{bucket="1_2"} 9121
telemt_desync_frames_bucket_total{bucket="3_10"} 14301
telemt_desync_frames_bucket_total{bucket="gt_10"} 13688
telemt_pool_swap_total 171
telemt_pool_force_close_total 5320
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 51298
telemt_me_writer_removed_unexpected_total 1571
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4763
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47948
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45978
telemt_me_writer_teardown_success_total{mode="normal"} 52711
telemt_me_writer_teardown_noop_total 51321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.934793
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1422
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 8281946
telemt_user_connections_current{user="hello"} 1711
telemt_user_octets_from_client{user="hello"} 207114610833 (192.89 GB)
telemt_user_octets_to_client{user="hello"} 3734106358538 (3.40 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 161342.1 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10561305
telemt_connections_bad_total 911163
telemt_connections_current 1123
telemt_connections_me_current 1123
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 337916
telemt_upstream_connect_attempt_total 70121
telemt_upstream_connect_success_total 69130
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 69312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2094
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4781
telemt_me_reconnect_success_total 1927
telemt_me_reader_eof_total 1679
telemt_me_idle_close_by_peer_total 1678
telemt_me_route_drop_no_conn_total 5165253
telemt_me_route_drop_channel_closed_total 367
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7968728
telemt_me_endpoint_quarantine_total 1099
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1188
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_me_writers_active_current 43
telemt_desync_total 36621
telemt_desync_full_logged_total 12112
telemt_desync_suppressed_total 24509
telemt_desync_frames_bucket_total{bucket="1_2"} 9275
telemt_desync_frames_bucket_total{bucket="3_10"} 14008
telemt_desync_frames_bucket_total{bucket="gt_10"} 13338
telemt_pool_swap_total 169
telemt_pool_force_close_total 5266
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 51792
telemt_me_writer_removed_unexpected_total 1821
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5193
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48333
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4724
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46526
telemt_me_writer_teardown_success_total{mode="normal"} 53526
telemt_me_writer_teardown_noop_total 51863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105389
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.873856
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105389
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1666
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 7961536
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 183781747649 (171.16 GB)
telemt_user_octets_to_client{user="hello"} 3311850518245 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 31621.8 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10350373
telemt_connections_bad_total 632435
telemt_connections_current 2243
telemt_connections_me_current 2243
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 200264
telemt_upstream_connect_attempt_total 41113
telemt_upstream_connect_success_total 39032
telemt_upstream_connect_fail_total 1480
telemt_upstream_connect_attempts_per_request{bucket="1"} 40512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11583
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5915
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1480
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6138
telemt_me_reconnect_success_total 782
telemt_me_reader_eof_total 484
telemt_me_idle_close_by_peer_total 484
telemt_me_route_drop_no_conn_total 25015234
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8606417
telemt_me_endpoint_quarantine_total 202
telemt_me_single_endpoint_outage_enter_total 59
telemt_me_single_endpoint_outage_exit_total 59
telemt_me_single_endpoint_outage_reconnect_attempt_total 110
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 110
telemt_me_single_endpoint_shadow_rotate_total 248
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
telemt_me_writers_active_current 42
telemt_desync_total 13643
telemt_desync_full_logged_total 3541
telemt_desync_suppressed_total 10102
telemt_desync_frames_bucket_total{bucket="1_2"} 2517
telemt_desync_frames_bucket_total{bucket="3_10"} 5527
telemt_desync_frames_bucket_total{bucket="gt_10"} 5599
telemt_pool_swap_total 31
telemt_pool_force_close_total 1160
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 8837
telemt_me_writer_removed_unexpected_total 687
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1408
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8078
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 878
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7677
telemt_me_writer_teardown_success_total{mode="normal"} 9486
telemt_me_writer_teardown_noop_total 8842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.857876
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 296
telemt_me_writer_restored_same_endpoint_total 523
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 8628162
telemt_user_connections_current{user="hello"} 2243
telemt_user_octets_from_client{user="hello"} 70164111555 (65.35 GB)
telemt_user_octets_to_client{user="hello"} 354964218473 (330.59 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 808
telemt_user_unique_ips_recent_window{user="hello"} 321
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 161348.5 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10374642
telemt_connections_bad_total 872934
telemt_connections_current 1411
telemt_connections_me_current 1411
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 229849
telemt_upstream_connect_attempt_total 98851
telemt_upstream_connect_success_total 97826
telemt_upstream_connect_fail_total 870
telemt_upstream_connect_attempts_per_request{bucket="1"} 98696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 870
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72092
telemt_me_reconnect_success_total 2665
telemt_me_reader_eof_total 2366
telemt_me_idle_close_by_peer_total 2364
telemt_me_route_drop_no_conn_total 5100707
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8184571
telemt_me_endpoint_quarantine_total 1085
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1203
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 42957
telemt_desync_full_logged_total 14646
telemt_desync_suppressed_total 28311
telemt_desync_frames_bucket_total{bucket="1_2"} 8741
telemt_desync_frames_bucket_total{bucket="3_10"} 16580
telemt_desync_frames_bucket_total{bucket="gt_10"} 17636
telemt_pool_swap_total 165
telemt_pool_force_close_total 4907
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 616
telemt_me_draining_writers_reap_progress_total 54900
telemt_me_writer_removed_unexpected_total 2408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5872
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51458
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4221
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 686
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49993
telemt_me_writer_teardown_success_total{mode="normal"} 57330
telemt_me_writer_teardown_noop_total 54901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112231
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.595674
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112231
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 616
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2233
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8188313
telemt_user_connections_current{user="hello"} 1411
telemt_user_octets_from_client{user="hello"} 185879477057 (173.11 GB)
telemt_user_octets_to_client{user="hello"} 3090678214976 (2.81 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 98184.6 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10827961
telemt_connections_bad_total 412997
telemt_connections_current 2089
telemt_connections_me_current 2089
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4518683
telemt_upstream_connect_attempt_total 46993
telemt_upstream_connect_success_total 46645
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 46984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_reconnect_attempts_total 48212
telemt_me_reconnect_success_total 1555
telemt_me_reader_eof_total 1215
telemt_me_idle_close_by_peer_total 1214
telemt_me_route_drop_no_conn_total 3953166
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5200178
telemt_me_endpoint_quarantine_total 634
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 736
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 36
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28785
telemt_desync_full_logged_total 9747
telemt_desync_suppressed_total 19038
telemt_desync_frames_bucket_total{bucket="1_2"} 5812
telemt_desync_frames_bucket_total{bucket="3_10"} 11351
telemt_desync_frames_bucket_total{bucket="gt_10"} 11622
telemt_pool_swap_total 103
telemt_pool_force_close_total 3164
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 329
telemt_me_draining_writers_reap_progress_total 33795
telemt_me_writer_removed_unexpected_total 1276
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3031
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32072
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2743
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 421
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30631
telemt_me_writer_teardown_success_total{mode="normal"} 35103
telemt_me_writer_teardown_noop_total 33802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68905
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.003781
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68905
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 329
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1383
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5193479
telemt_user_connections_current{user="hello"} 2089
telemt_user_octets_from_client{user="hello"} 112057706904 (104.36 GB)
telemt_user_octets_to_client{user="hello"} 1969916028446 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 789
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 79155.9 (21h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1105553
telemt_connections_bad_total 17529
telemt_connections_current 1167
telemt_connections_me_current 1167
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20840
telemt_upstream_connect_attempt_total 38389
telemt_upstream_connect_success_total 38278
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 38365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 587
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_reconnect_attempts_total 1744
telemt_me_reconnect_success_total 737
telemt_me_reader_eof_total 711
telemt_me_idle_close_by_peer_total 711
telemt_me_route_drop_no_conn_total 386220
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 984069
telemt_me_endpoint_quarantine_total 669
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 651
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
telemt_desync_total 5621
telemt_desync_full_logged_total 1711
telemt_desync_suppressed_total 3910
telemt_desync_frames_bucket_total{bucket="1_2"} 1338
telemt_desync_frames_bucket_total{bucket="3_10"} 2206
telemt_desync_frames_bucket_total{bucket="gt_10"} 2077
telemt_pool_swap_total 84
telemt_pool_force_close_total 2148
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 31827
telemt_me_writer_removed_unexpected_total 687
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2466
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2065
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29679
telemt_me_writer_teardown_success_total{mode="normal"} 32540
telemt_me_writer_teardown_noop_total 31830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64370
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.807624
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64370
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 627
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 980519
telemt_user_connections_current{user="hello"} 1167
telemt_user_octets_from_client{user="hello"} 18169110697 (16.92 GB)
telemt_user_octets_to_client{user="hello"} 423779771003 (394.68 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 161353.2 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12657213
telemt_connections_bad_total 1469640
telemt_connections_current 1594
telemt_connections_me_current 1594
telemt_handshake_timeouts_total 352795
telemt_upstream_connect_attempt_total 60732
telemt_upstream_connect_success_total 60452
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 60640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_reconnect_attempts_total 2379
telemt_me_reconnect_success_total 1260
telemt_me_reader_eof_total 1222
telemt_me_idle_close_by_peer_total 1222
telemt_me_route_drop_no_conn_total 4231477
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9573484
telemt_me_endpoint_quarantine_total 1083
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1206
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
telemt_me_writers_active_current 44
telemt_desync_total 39314
telemt_desync_full_logged_total 12832
telemt_desync_suppressed_total 26482
telemt_desync_frames_bucket_total{bucket="1_2"} 9369
telemt_desync_frames_bucket_total{bucket="3_10"} 14559
telemt_desync_frames_bucket_total{bucket="gt_10"} 15386
telemt_pool_swap_total 179
telemt_pool_force_close_total 4937
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 632
telemt_me_draining_writers_reap_progress_total 54662
telemt_me_writer_removed_unexpected_total 1174
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4498
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51372
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4763
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49725
telemt_me_writer_teardown_success_total{mode="normal"} 55870
telemt_me_writer_teardown_noop_total 54664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110534
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.507648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110534
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 632
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1100
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 9542588
telemt_user_connections_current{user="hello"} 1594
telemt_user_octets_from_client{user="hello"} 187074286760 (174.23 GB)
telemt_user_octets_to_client{user="hello"} 4215717033036 (3.83 TB)
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 161349.5 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10975375
telemt_connections_bad_total 1225880
telemt_connections_current 1650
telemt_connections_me_current 1650
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 284612
telemt_upstream_connect_attempt_total 86549
telemt_upstream_connect_success_total 85830
telemt_upstream_connect_fail_total 575
telemt_upstream_connect_attempts_per_request{bucket="1"} 86405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 575
telemt_me_reconnect_attempts_total 9122
telemt_me_reconnect_success_total 2145
telemt_me_reader_eof_total 2001
telemt_me_idle_close_by_peer_total 2001
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5477841
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8490434
telemt_me_endpoint_quarantine_total 1222
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1209
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38691
telemt_desync_full_logged_total 12494
telemt_desync_suppressed_total 26197
telemt_desync_frames_bucket_total{bucket="1_2"} 9625
telemt_desync_frames_bucket_total{bucket="3_10"} 14408
telemt_desync_frames_bucket_total{bucket="gt_10"} 14658
telemt_pool_swap_total 170
telemt_pool_force_close_total 4752
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 54032
telemt_me_writer_removed_unexpected_total 2026
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5633
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50495
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4313
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49280
telemt_me_writer_teardown_success_total{mode="normal"} 56128
telemt_me_writer_teardown_noop_total 54037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110165
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.712320
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110165
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1744
telemt_me_writer_restored_fallback_total 101
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 8496350
telemt_user_connections_current{user="hello"} 1650
telemt_user_octets_from_client{user="hello"} 149406871921 (139.15 GB)
telemt_user_octets_to_client{user="hello"} 3253806761943 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 676
telemt_user_unique_ips_recent_window{user="hello"} 193
```