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

# Server Metrics 2026-03-21 20:59:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 87841.1 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3116333
telemt_connections_bad_total 180544
telemt_connections_current 1024
telemt_connections_me_current 1024
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 97538
telemt_upstream_connect_attempt_total 35849
telemt_upstream_connect_success_total 35699
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 35806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1935
telemt_me_reconnect_success_total 772
telemt_me_reader_eof_total 741
telemt_me_idle_close_by_peer_total 741
telemt_me_route_drop_no_conn_total 2631936
telemt_me_route_drop_channel_closed_total 847
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2519317
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 686
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 10074
telemt_desync_full_logged_total 3524
telemt_desync_suppressed_total 6550
telemt_desync_frames_bucket_total{bucket="1_2"} 2182
telemt_desync_frames_bucket_total{bucket="3_10"} 3771
telemt_desync_frames_bucket_total{bucket="gt_10"} 4121
telemt_pool_swap_total 95
telemt_pool_force_close_total 2871
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 646
telemt_me_draining_writers_reap_progress_total 29459
telemt_me_writer_removed_unexpected_total 722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2462
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27460
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 140
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26588
telemt_me_writer_teardown_success_total{mode="normal"} 29922
telemt_me_writer_teardown_noop_total 29467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59389
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 300.791423
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59389
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 646
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 663
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2518888
telemt_user_connections_current{user="hello"} 1024
telemt_user_octets_from_client{user="hello"} 37270787933 (34.71 GB)
telemt_user_octets_to_client{user="hello"} 645310213826 (600.99 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 12978.9 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503868
telemt_connections_bad_total 22970
telemt_connections_current 797
telemt_connections_me_current 797
telemt_handshake_timeouts_total 17702
telemt_upstream_connect_attempt_total 5144
telemt_upstream_connect_success_total 5039
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 5131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_reconnect_attempts_total 367
telemt_me_reconnect_success_total 162
telemt_me_reader_eof_total 139
telemt_me_idle_close_by_peer_total 139
telemt_me_route_drop_no_conn_total 286577
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408654
telemt_me_endpoint_quarantine_total 97
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 1763
telemt_desync_full_logged_total 1010
telemt_desync_suppressed_total 753
telemt_desync_frames_bucket_total{bucket="1_2"} 358
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 731
telemt_pool_swap_total 14
telemt_pool_force_close_total 420
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 4466
telemt_me_writer_removed_unexpected_total 131
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 386
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4206
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 413
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4046
telemt_me_writer_teardown_success_total{mode="normal"} 4592
telemt_me_writer_teardown_noop_total 4466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9058
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.868698
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9058
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 111
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 408140
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 6710680952 (6.25 GB)
telemt_user_octets_to_client{user="hello"} 127261368820 (118.52 GB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 87838.8 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6982294
telemt_connections_bad_total 540071
telemt_connections_current 3345
telemt_connections_me_current 3345
telemt_handshake_timeouts_total 218494
telemt_upstream_connect_attempt_total 31509
telemt_upstream_connect_success_total 31446
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 31453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1352
telemt_me_reconnect_success_total 675
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 4386908
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5711379
telemt_me_endpoint_quarantine_total 544
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 651
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
telemt_me_writers_active_current 47
telemt_desync_total 23677
telemt_desync_full_logged_total 7883
telemt_desync_suppressed_total 15794
telemt_desync_frames_bucket_total{bucket="1_2"} 4947
telemt_desync_frames_bucket_total{bucket="3_10"} 9376
telemt_desync_frames_bucket_total{bucket="gt_10"} 9354
telemt_pool_swap_total 94
telemt_pool_force_close_total 3182
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 517
telemt_me_draining_writers_reap_progress_total 28698
telemt_me_writer_removed_unexpected_total 658
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2460
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26499
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25516
telemt_me_writer_teardown_success_total{mode="normal"} 28959
telemt_me_writer_teardown_noop_total 28735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57694
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 141.846105
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57694
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 517
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 604
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 5704478
telemt_user_connections_current{user="hello"} 3345
telemt_user_octets_from_client{user="hello"} 98277858516 (91.53 GB)
telemt_user_octets_to_client{user="hello"} 1806250606940 (1.64 TB)
telemt_user_unique_ips_current{user="hello"} 1371
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 87840.9 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5664905
telemt_connections_bad_total 549203
telemt_connections_current 3165
telemt_connections_me_current 3165
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 185188
telemt_upstream_connect_attempt_total 35589
telemt_upstream_connect_success_total 35271
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 35435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1674
telemt_me_reconnect_success_total 700
telemt_me_reader_eof_total 674
telemt_me_idle_close_by_peer_total 674
telemt_me_route_drop_no_conn_total 1958263
telemt_me_route_drop_channel_closed_total 224
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4235246
telemt_me_endpoint_quarantine_total 539
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 670
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 20218
telemt_desync_full_logged_total 6721
telemt_desync_suppressed_total 13497
telemt_desync_frames_bucket_total{bucket="1_2"} 4936
telemt_desync_frames_bucket_total{bucket="3_10"} 7819
telemt_desync_frames_bucket_total{bucket="gt_10"} 7463
telemt_pool_swap_total 96
telemt_pool_force_close_total 2916
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 331
telemt_me_draining_writers_reap_progress_total 27439
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25646
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2719
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 197
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24523
telemt_me_writer_teardown_success_total{mode="normal"} 28021
telemt_me_writer_teardown_noop_total 27444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55465
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.631753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55465
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 331
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 600
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4227105
telemt_user_connections_current{user="hello"} 3165
telemt_user_octets_from_client{user="hello"} 127532228853 (118.77 GB)
telemt_user_octets_to_client{user="hello"} 1944092551263 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1259
telemt_user_unique_ips_recent_window{user="hello"} 376
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 87804.7 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5584207
telemt_connections_bad_total 501753
telemt_connections_current 2628
telemt_connections_me_current 2628
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 170637
telemt_upstream_connect_attempt_total 42032
telemt_upstream_connect_success_total 41758
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 41893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1731
telemt_me_reconnect_success_total 764
telemt_me_reader_eof_total 708
telemt_me_idle_close_by_peer_total 708
telemt_me_route_drop_no_conn_total 2007743
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4217862
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 655
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
telemt_me_writers_active_current 43
telemt_desync_total 19984
telemt_desync_full_logged_total 6545
telemt_desync_suppressed_total 13439
telemt_desync_frames_bucket_total{bucket="1_2"} 4966
telemt_desync_frames_bucket_total{bucket="3_10"} 7574
telemt_desync_frames_bucket_total{bucket="gt_10"} 7444
telemt_pool_swap_total 94
telemt_pool_force_close_total 2795
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 335
telemt_me_draining_writers_reap_progress_total 28906
telemt_me_writer_removed_unexpected_total 678
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2467
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27120
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2582
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26111
telemt_me_writer_teardown_success_total{mode="normal"} 29587
telemt_me_writer_teardown_noop_total 28916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58503
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.375840
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58503
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 335
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4219883
telemt_user_connections_current{user="hello"} 2628
telemt_user_octets_from_client{user="hello"} 122921607703 (114.48 GB)
telemt_user_octets_to_client{user="hello"} 1926992034119 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1120
telemt_user_unique_ips_recent_window{user="hello"} 366
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 87843.4 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19227081
telemt_connections_bad_total 1264398
telemt_connections_current 3574
telemt_connections_me_current 3574
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 537214
telemt_upstream_connect_attempt_total 181520
telemt_upstream_connect_success_total 164279
telemt_upstream_connect_fail_total 15805
telemt_upstream_connect_attempts_per_request{bucket="1"} 180084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8849
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15805
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59635
telemt_me_reconnect_success_total 1892
telemt_me_reader_eof_total 1249
telemt_me_idle_close_by_peer_total 1248
telemt_me_route_drop_no_conn_total 39133679
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15796777
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 645
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 684
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
telemt_me_writers_active_current 86
telemt_desync_total 29667
telemt_desync_full_logged_total 8756
telemt_desync_suppressed_total 20911
telemt_desync_frames_bucket_total{bucket="1_2"} 6502
telemt_desync_frames_bucket_total{bucket="3_10"} 13135
telemt_desync_frames_bucket_total{bucket="gt_10"} 10030
telemt_pool_swap_total 89
telemt_pool_force_close_total 2975
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 27003
telemt_me_writer_removed_unexpected_total 1782
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3700
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24829
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24028
telemt_me_writer_teardown_success_total{mode="normal"} 28529
telemt_me_writer_teardown_noop_total 27029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55558
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.335626
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55558
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1316
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14223
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 15922001
telemt_user_connections_current{user="hello"} 3574
telemt_user_octets_from_client{user="hello"} 154994902358 (144.35 GB)
telemt_user_octets_to_client{user="hello"} 982886163402 (915.38 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1451
telemt_user_unique_ips_recent_window{user="hello"} 477
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 87810.7 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5482253
telemt_connections_bad_total 525275
telemt_connections_current 3061
telemt_connections_me_current 3061
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 112757
telemt_upstream_connect_attempt_total 45157
telemt_upstream_connect_success_total 44662
telemt_upstream_connect_fail_total 411
telemt_upstream_connect_attempts_per_request{bucket="1"} 45073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 411
telemt_me_reconnect_attempts_total 11082
telemt_me_reconnect_success_total 1278
telemt_me_reader_eof_total 1205
telemt_me_idle_close_by_peer_total 1205
telemt_me_route_drop_no_conn_total 2281319
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4257814
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 653
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
telemt_me_writers_active_current 45
telemt_desync_total 21135
telemt_desync_full_logged_total 7333
telemt_desync_suppressed_total 13802
telemt_desync_frames_bucket_total{bucket="1_2"} 4040
telemt_desync_frames_bucket_total{bucket="3_10"} 8227
telemt_desync_frames_bucket_total{bucket="gt_10"} 8868
telemt_pool_swap_total 89
telemt_pool_force_close_total 2637
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 330
telemt_me_draining_writers_reap_progress_total 29711
telemt_me_writer_removed_unexpected_total 1185
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3026
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27883
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2272
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 365
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27074
telemt_me_writer_teardown_success_total{mode="normal"} 30909
telemt_me_writer_teardown_noop_total 29712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60621
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.456707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60621
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 330
telemt_me_refill_failed_total 591
telemt_me_writer_restored_same_endpoint_total 1079
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4247414
telemt_user_connections_current{user="hello"} 3061
telemt_user_octets_from_client{user="hello"} 113951879325 (106.13 GB)
telemt_user_octets_to_client{user="hello"} 1722772394507 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1288
telemt_user_unique_ips_recent_window{user="hello"} 391
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 24646.4 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3223021
telemt_connections_bad_total 118418
telemt_connections_current 2493
telemt_connections_me_current 2493
telemt_handshake_timeouts_total 1379431
telemt_upstream_connect_attempt_total 8051
telemt_upstream_connect_success_total 7944
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 8045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 2215
telemt_me_reconnect_success_total 273
telemt_me_reader_eof_total 214
telemt_me_idle_close_by_peer_total 214
telemt_me_route_drop_no_conn_total 926787
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1529564
telemt_me_endpoint_quarantine_total 123
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 184
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
telemt_desync_total 8490
telemt_desync_full_logged_total 2820
telemt_desync_suppressed_total 5670
telemt_desync_frames_bucket_total{bucket="1_2"} 1514
telemt_desync_frames_bucket_total{bucket="3_10"} 3220
telemt_desync_frames_bucket_total{bucket="gt_10"} 3756
telemt_pool_swap_total 26
telemt_pool_force_close_total 846
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 6996
telemt_me_writer_removed_unexpected_total 231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 662
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6573
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 737
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6150
telemt_me_writer_teardown_success_total{mode="normal"} 7235
telemt_me_writer_teardown_noop_total 6997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14232
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.185250
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14232
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1525128
telemt_user_connections_current{user="hello"} 2493
telemt_user_octets_from_client{user="hello"} 45154557448 (42.05 GB)
telemt_user_octets_to_client{user="hello"} 638428516464 (594.58 GB)
telemt_user_unique_ips_current{user="hello"} 1054
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 5617.8 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61762
telemt_connections_bad_total 177
telemt_connections_current 621
telemt_connections_me_current 621
telemt_handshake_timeouts_total 852
telemt_upstream_connect_attempt_total 2456
telemt_upstream_connect_success_total 2448
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 58
telemt_me_reconnect_success_total 27
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 18267
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54891
telemt_me_endpoint_quarantine_total 39
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
telemt_me_writers_active_current 43
telemt_desync_total 392
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 271
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 6
telemt_pool_force_close_total 160
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 2133
telemt_me_writer_removed_unexpected_total 27
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 143
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2017
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 160
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1973
telemt_me_writer_teardown_success_total{mode="normal"} 2160
telemt_me_writer_teardown_noop_total 2133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4293
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.298940
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4293
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 54800
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 1153952376 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 41651942572 (38.79 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 87815.2 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6508194
telemt_connections_bad_total 663562
telemt_connections_current 3408
telemt_connections_me_current 3408
telemt_handshake_timeouts_total 187993
telemt_upstream_connect_attempt_total 33261
telemt_upstream_connect_success_total 33128
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 33224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_reconnect_attempts_total 1399
telemt_me_reconnect_success_total 705
telemt_me_reader_eof_total 679
telemt_me_idle_close_by_peer_total 679
telemt_me_route_drop_no_conn_total 2009129
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4988703
telemt_me_endpoint_quarantine_total 585
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 669
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
telemt_me_writers_active_current 46
telemt_desync_total 19014
telemt_desync_full_logged_total 6343
telemt_desync_suppressed_total 12671
telemt_desync_frames_bucket_total{bucket="1_2"} 4629
telemt_desync_frames_bucket_total{bucket="3_10"} 6930
telemt_desync_frames_bucket_total{bucket="gt_10"} 7455
telemt_pool_swap_total 97
telemt_pool_force_close_total 2652
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 336
telemt_me_draining_writers_reap_progress_total 29873
telemt_me_writer_removed_unexpected_total 662
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28117
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2568
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27221
telemt_me_writer_teardown_success_total{mode="normal"} 30542
telemt_me_writer_teardown_noop_total 29875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60417
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.867451
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60417
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 336
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 629
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4964500
telemt_user_connections_current{user="hello"} 3408
telemt_user_octets_from_client{user="hello"} 98982663692 (92.18 GB)
telemt_user_octets_to_client{user="hello"} 2321032512712 (2.11 TB)
telemt_user_unique_ips_current{user="hello"} 1302
telemt_user_unique_ips_recent_window{user="hello"} 388
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 87811.9 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5526318
telemt_connections_bad_total 517907
telemt_connections_current 2959
telemt_connections_me_current 2959
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 158482
telemt_upstream_connect_attempt_total 49620
telemt_upstream_connect_success_total 49251
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 49561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_reconnect_attempts_total 4519
telemt_me_reconnect_success_total 998
telemt_me_reader_eof_total 885
telemt_me_idle_close_by_peer_total 885
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2065056
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4352513
telemt_me_endpoint_quarantine_total 693
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 668
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
telemt_me_writers_active_current 42
telemt_desync_total 17727
telemt_desync_full_logged_total 5974
telemt_desync_suppressed_total 11753
telemt_desync_frames_bucket_total{bucket="1_2"} 4383
telemt_desync_frames_bucket_total{bucket="3_10"} 6513
telemt_desync_frames_bucket_total{bucket="gt_10"} 6831
telemt_pool_swap_total 95
telemt_pool_force_close_total 2583
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 333
telemt_me_draining_writers_reap_progress_total 29057
telemt_me_writer_removed_unexpected_total 897
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2914
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27081
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2385
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26474
telemt_me_writer_teardown_success_total{mode="normal"} 29995
telemt_me_writer_teardown_noop_total 29061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59056
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.027282
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59056
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 333
telemt_me_refill_failed_total 201
telemt_me_writer_restored_same_endpoint_total 769
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4356531
telemt_user_connections_current{user="hello"} 2959
telemt_user_octets_from_client{user="hello"} 83462693669 (77.73 GB)
telemt_user_octets_to_client{user="hello"} 1833146416384 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1173
telemt_user_unique_ips_recent_window{user="hello"} 352
```