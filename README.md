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

# Server Metrics 2026-03-23 06:41:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 120929.9 (33h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4359414
telemt_connections_bad_total 415197
telemt_connections_current 1648
telemt_connections_me_current 1648
telemt_handshake_timeouts_total 149866
telemt_upstream_connect_attempt_total 44876
telemt_upstream_connect_success_total 44875
telemt_upstream_connect_attempts_per_request{bucket="1"} 44875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29129
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1566
telemt_me_reconnect_success_total 709
telemt_me_reader_eof_total 734
telemt_me_idle_close_by_peer_total 734
telemt_me_route_drop_no_conn_total 3587272
telemt_me_route_drop_channel_closed_total 1397
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3563577
telemt_me_writer_pick_total{mode="p2c",result="full"} 22
telemt_me_endpoint_quarantine_total 856
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 947
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
telemt_me_writers_active_current 47
telemt_desync_total 14817
telemt_desync_full_logged_total 4709
telemt_desync_suppressed_total 10108
telemt_desync_frames_bucket_total{bucket="1_2"} 3823
telemt_desync_frames_bucket_total{bucket="3_10"} 5545
telemt_desync_frames_bucket_total{bucket="gt_10"} 5449
telemt_pool_swap_total 134
telemt_pool_force_close_total 4129
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 794
telemt_me_draining_writers_reap_progress_total 41105
telemt_me_writer_removed_unexpected_total 706
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38416
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36976
telemt_me_writer_teardown_success_total{mode="normal"} 41382
telemt_me_writer_teardown_noop_total 41118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82500
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 456.143674
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82500
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 794
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 3550759
telemt_user_connections_current{user="hello"} 1648
telemt_user_octets_from_client{user="hello"} 46869666292 (43.65 GB)
telemt_user_octets_to_client{user="hello"} 923911594176 (860.46 GB)
telemt_user_unique_ips_current{user="hello"} 648
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 134296.9 (37h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4232698
telemt_connections_bad_total 394346
telemt_connections_current 1094
telemt_connections_me_current 1094
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 112234
telemt_upstream_connect_attempt_total 83542
telemt_upstream_connect_success_total 82530
telemt_upstream_connect_fail_total 900
telemt_upstream_connect_attempts_per_request{bucket="1"} 83430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 900
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11194
telemt_me_reconnect_success_total 4068
telemt_me_reader_eof_total 4043
telemt_me_idle_close_by_peer_total 4042
telemt_me_route_drop_no_conn_total 3691357
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3356275
telemt_me_endpoint_quarantine_total 1085
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1060
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
telemt_me_writers_active_current 118
telemt_me_writers_warm_current 23
telemt_desync_total 13906
telemt_desync_full_logged_total 7856
telemt_desync_suppressed_total 6050
telemt_desync_frames_bucket_total{bucket="1_2"} 3142
telemt_desync_frames_bucket_total{bucket="3_10"} 5458
telemt_desync_frames_bucket_total{bucket="gt_10"} 5306
telemt_pool_swap_total 125
telemt_pool_force_close_total 3492
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 272
telemt_me_draining_writers_reap_progress_total 56540
telemt_me_writer_removed_unexpected_total 3958
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7128
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53420
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53048
telemt_me_writer_teardown_success_total{mode="normal"} 60548
telemt_me_writer_teardown_noop_total 56541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117089
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.036234
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117089
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 272
telemt_me_refill_failed_total 283
telemt_me_writer_restored_same_endpoint_total 3608
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 3370615
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 45481630843 (42.36 GB)
telemt_user_octets_to_client{user="hello"} 859018943861 (800.02 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 619
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 209157.1 (58h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16861987
telemt_connections_bad_total 1713453
telemt_connections_current 1933
telemt_connections_me_current 1933
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 418400
telemt_upstream_connect_attempt_total 93926
telemt_upstream_connect_success_total 93815
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 93832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1736
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3385
telemt_me_reconnect_success_total 1756
telemt_me_reader_eof_total 1715
telemt_me_idle_close_by_peer_total 1712
telemt_me_route_drop_no_conn_total 14167445
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13392779
telemt_me_endpoint_quarantine_total 1423
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1585
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 56244
telemt_desync_full_logged_total 17988
telemt_desync_suppressed_total 38256
telemt_desync_frames_bucket_total{bucket="1_2"} 12491
telemt_desync_frames_bucket_total{bucket="3_10"} 22041
telemt_desync_frames_bucket_total{bucket="gt_10"} 21712
telemt_pool_swap_total 226
telemt_pool_force_close_total 7254
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1123
telemt_me_draining_writers_reap_progress_total 72541
telemt_me_writer_removed_unexpected_total 1648
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6114
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67361
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6755
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 499
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65287
telemt_me_writer_teardown_success_total{mode="normal"} 73475
telemt_me_writer_teardown_noop_total 72595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 320.077096
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1123
telemt_me_refill_failed_total 90
telemt_me_writer_restored_same_endpoint_total 1523
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 13392473
telemt_user_connections_current{user="hello"} 1933
telemt_user_octets_from_client{user="hello"} 202564099813 (188.65 GB)
telemt_user_octets_to_client{user="hello"} 3659140174099 (3.33 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 712
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 209158.1 (58h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12308216
telemt_connections_bad_total 1312438
telemt_connections_current 1341
telemt_connections_me_current 1341
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 356631
telemt_upstream_connect_attempt_total 108146
telemt_upstream_connect_success_total 106729
telemt_upstream_connect_fail_total 903
telemt_upstream_connect_attempts_per_request{bucket="1"} 107632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 903
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4786
telemt_me_reconnect_success_total 2068
telemt_me_reader_eof_total 1920
telemt_me_idle_close_by_peer_total 1920
telemt_me_route_drop_no_conn_total 4643746
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9101745
telemt_me_endpoint_quarantine_total 1433
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1601
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_me_writers_active_current 44
telemt_desync_total 40069
telemt_desync_full_logged_total 13555
telemt_desync_suppressed_total 26514
telemt_desync_frames_bucket_total{bucket="1_2"} 9947
telemt_desync_frames_bucket_total{bucket="3_10"} 15377
telemt_desync_frames_bucket_total{bucket="gt_10"} 14745
telemt_pool_swap_total 224
telemt_pool_force_close_total 6612
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 725
telemt_me_draining_writers_reap_progress_total 70493
telemt_me_writer_removed_unexpected_total 1949
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6170
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66136
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6097
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63881
telemt_me_writer_teardown_success_total{mode="normal"} 72306
telemt_me_writer_teardown_noop_total 70518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 105.123014
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 725
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1760
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 9039199
telemt_user_connections_current{user="hello"} 1341
telemt_user_octets_from_client{user="hello"} 221385455848 (206.18 GB)
telemt_user_octets_to_client{user="hello"} 4062469908787 (3.69 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 509
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 209121.1 (58h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11437468
telemt_connections_bad_total 1052926
telemt_connections_current 1114
telemt_connections_me_current 1114
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 362984
telemt_upstream_connect_attempt_total 92600
telemt_upstream_connect_success_total 91010
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 91215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5956
telemt_me_reconnect_success_total 2520
telemt_me_reader_eof_total 2257
telemt_me_idle_close_by_peer_total 2256
telemt_me_route_drop_no_conn_total 5410965
telemt_me_route_drop_channel_closed_total 390
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8599208
telemt_me_endpoint_quarantine_total 1483
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1566
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_me_writers_active_current 44
telemt_desync_total 39107
telemt_desync_full_logged_total 13012
telemt_desync_suppressed_total 26095
telemt_desync_frames_bucket_total{bucket="1_2"} 9864
telemt_desync_frames_bucket_total{bucket="3_10"} 14960
telemt_desync_frames_bucket_total{bucket="gt_10"} 14283
telemt_pool_swap_total 220
telemt_pool_force_close_total 6495
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 770
telemt_me_draining_writers_reap_progress_total 71129
telemt_me_writer_removed_unexpected_total 2402
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6916
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66552
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 577
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64634
telemt_me_writer_teardown_success_total{mode="normal"} 73468
telemt_me_writer_teardown_noop_total 71200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144668
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.561548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144668
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 770
telemt_me_refill_failed_total 182
telemt_me_writer_restored_same_endpoint_total 2188
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 8590898
telemt_user_connections_current{user="hello"} 1114
telemt_user_octets_from_client{user="hello"} 195009260003 (181.62 GB)
telemt_user_octets_to_client{user="hello"} 3563654150581 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 79401.8 (22h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11931590
telemt_connections_bad_total 727676
telemt_connections_current 2377
telemt_connections_me_current 2377
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 340304
telemt_upstream_connect_attempt_total 79417
telemt_upstream_connect_success_total 75462
telemt_upstream_connect_fail_total 2650
telemt_upstream_connect_attempts_per_request{bucket="1"} 78112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2650
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8684
telemt_me_reconnect_success_total 1635
telemt_me_reader_eof_total 1044
telemt_me_idle_close_by_peer_total 1043
telemt_me_route_drop_no_conn_total 25450006
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9831108
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 114
telemt_me_single_endpoint_outage_exit_total 114
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 59
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 638
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
telemt_me_writers_active_current 44
telemt_desync_total 17670
telemt_desync_full_logged_total 4978
telemt_desync_suppressed_total 12692
telemt_desync_frames_bucket_total{bucket="1_2"} 3442
telemt_desync_frames_bucket_total{bucket="3_10"} 7218
telemt_desync_frames_bucket_total{bucket="gt_10"} 7010
telemt_pool_swap_total 82
telemt_pool_force_close_total 2505
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 559
telemt_me_draining_writers_reap_progress_total 26371
telemt_me_writer_removed_unexpected_total 1497
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3431
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24384
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 352
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23866
telemt_me_writer_teardown_success_total{mode="normal"} 27815
telemt_me_writer_teardown_noop_total 26390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54205
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.520622
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54205
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 559
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 1043
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3157
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 9868478
telemt_user_connections_current{user="hello"} 2377
telemt_user_octets_from_client{user="hello"} 92776541271 (86.40 GB)
telemt_user_octets_to_client{user="hello"} 786796821265 (732.76 GB)
telemt_user_msgs_from_client{user="hello"} 101207
telemt_user_msgs_to_client{user="hello"} 147658
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 209127.6 (58h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11445692
telemt_connections_bad_total 1009584
telemt_connections_current 1589
telemt_connections_me_current 1589
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 261491
telemt_upstream_connect_attempt_total 121957
telemt_upstream_connect_success_total 120652
telemt_upstream_connect_fail_total 1124
telemt_upstream_connect_attempts_per_request{bucket="1"} 121776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1124
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73807
telemt_me_reconnect_success_total 3407
telemt_me_reader_eof_total 3085
telemt_me_idle_close_by_peer_total 3082
telemt_me_route_drop_no_conn_total 5363349
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9006610
telemt_me_endpoint_quarantine_total 1431
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1590
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_active_current 89
telemt_desync_total 47811
telemt_desync_full_logged_total 16469
telemt_desync_suppressed_total 31342
telemt_desync_frames_bucket_total{bucket="1_2"} 9738
telemt_desync_frames_bucket_total{bucket="3_10"} 18311
telemt_desync_frames_bucket_total{bucket="gt_10"} 19762
telemt_pool_swap_total 214
telemt_pool_force_close_total 6170
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 75460
telemt_me_writer_removed_unexpected_total 3101
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7532
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71077
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5400
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 770
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69290
telemt_me_writer_teardown_success_total{mode="normal"} 78609
telemt_me_writer_teardown_noop_total 75461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 154026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 154060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 154063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 154063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 154066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 154070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 154070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 154070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 154070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 154070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.509452
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 154070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2875
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 9009184
telemt_user_connections_current{user="hello"} 1589
telemt_user_octets_from_client{user="hello"} 200489383049 (186.72 GB)
telemt_user_octets_to_client{user="hello"} 3453298681744 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 647
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 145964.0 (40h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12275105
telemt_connections_bad_total 509985
telemt_connections_current 1358
telemt_connections_me_current 1358
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4943246
telemt_upstream_connect_attempt_total 70568
telemt_upstream_connect_success_total 70063
telemt_upstream_connect_fail_total 492
telemt_upstream_connect_attempts_per_request{bucket="1"} 70555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 492
telemt_me_reconnect_attempts_total 49498
telemt_me_reconnect_success_total 2022
telemt_me_reader_eof_total 1702
telemt_me_idle_close_by_peer_total 1701
telemt_me_route_drop_no_conn_total 4177549
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5896492
telemt_me_endpoint_quarantine_total 1005
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1125
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 33185
telemt_desync_full_logged_total 11389
telemt_desync_suppressed_total 21796
telemt_desync_frames_bucket_total{bucket="1_2"} 6671
telemt_desync_frames_bucket_total{bucket="3_10"} 13053
telemt_desync_frames_bucket_total{bucket="gt_10"} 13461
telemt_pool_swap_total 156
telemt_pool_force_close_total 4363
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 55166
telemt_me_writer_removed_unexpected_total 1737
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4384
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52579
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3917
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 446
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50803
telemt_me_writer_teardown_success_total{mode="normal"} 56963
telemt_me_writer_teardown_noop_total 55173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.115634
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 2758
telemt_me_writer_restored_same_endpoint_total 1785
telemt_me_writer_restored_fallback_total 31
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4336
telemt_user_connections_total{user="hello"} 5888289
telemt_user_connections_current{user="hello"} 1358
telemt_user_octets_from_client{user="hello"} 122958358344 (114.51 GB)
telemt_user_octets_to_client{user="hello"} 2299520128770 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 126934.8 (35h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1839075
telemt_connections_bad_total 37849
telemt_connections_current 1075
telemt_connections_me_current 1075
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 40769
telemt_upstream_connect_attempt_total 59313
telemt_upstream_connect_success_total 59114
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 59274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 875
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 2565
telemt_me_reconnect_success_total 1039
telemt_me_reader_eof_total 1037
telemt_me_idle_close_by_peer_total 1037
telemt_me_route_drop_no_conn_total 738332
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1635298
telemt_me_endpoint_quarantine_total 1069
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1042
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 8
telemt_desync_total 10857
telemt_desync_full_logged_total 3060
telemt_desync_suppressed_total 7797
telemt_desync_frames_bucket_total{bucket="1_2"} 3462
telemt_desync_frames_bucket_total{bucket="3_10"} 4058
telemt_desync_frames_bucket_total{bucket="gt_10"} 3337
telemt_pool_swap_total 137
telemt_pool_force_close_total 3473
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 50632
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3821
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47858
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3384
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 89
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47159
telemt_me_writer_teardown_success_total{mode="normal"} 51679
telemt_me_writer_teardown_noop_total 50636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102315
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.758026
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102315
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 892
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1630824
telemt_user_connections_current{user="hello"} 1075
telemt_user_octets_from_client{user="hello"} 28594917081 (26.63 GB)
telemt_user_octets_to_client{user="hello"} 631832510747 (588.44 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 209132.8 (58h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13729351
telemt_connections_bad_total 1668235
telemt_connections_current 1653
telemt_connections_me_current 1653
telemt_handshake_timeouts_total 402784
telemt_upstream_connect_attempt_total 84506
telemt_upstream_connect_success_total 84136
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 84369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3316
telemt_me_reconnect_success_total 1662
telemt_me_reader_eof_total 1653
telemt_me_idle_close_by_peer_total 1653
telemt_me_route_drop_no_conn_total 4564807
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10353057
telemt_me_endpoint_quarantine_total 1550
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1592
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
telemt_me_writers_active_current 45
telemt_desync_total 43614
telemt_desync_full_logged_total 14185
telemt_desync_suppressed_total 29429
telemt_desync_frames_bucket_total{bucket="1_2"} 10614
telemt_desync_frames_bucket_total{bucket="3_10"} 16036
telemt_desync_frames_bucket_total{bucket="gt_10"} 16964
telemt_pool_swap_total 232
telemt_pool_force_close_total 6039
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 76520
telemt_me_writer_removed_unexpected_total 1580
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5871
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 72292
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5865
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70481
telemt_me_writer_teardown_success_total{mode="normal"} 78163
telemt_me_writer_teardown_noop_total 76522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 154176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 154552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 154672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 154685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 154685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 154685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 154685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 154685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 154685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 154685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 154685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.212891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 154685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1460
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10319327
telemt_user_connections_current{user="hello"} 1653
telemt_user_octets_from_client{user="hello"} 198310831892 (184.69 GB)
telemt_user_octets_to_client{user="hello"} 4607649650392 (4.19 TB)
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 209129.2 (58h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12054387
telemt_connections_bad_total 1429956
telemt_connections_current 1517
telemt_connections_me_current 1517
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 324011
telemt_upstream_connect_attempt_total 112518
telemt_upstream_connect_success_total 111555
telemt_upstream_connect_fail_total 754
telemt_upstream_connect_attempts_per_request{bucket="1"} 112309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 754
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11333
telemt_me_reconnect_success_total 2815
telemt_me_reader_eof_total 2614
telemt_me_idle_close_by_peer_total 2613
telemt_me_seq_mismatch_total 114
telemt_me_route_drop_no_conn_total 5733714
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9270336
telemt_me_endpoint_quarantine_total 1744
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1598
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 43540
telemt_desync_full_logged_total 13909
telemt_desync_suppressed_total 29631
telemt_desync_frames_bucket_total{bucket="1_2"} 11272
telemt_desync_frames_bucket_total{bucket="3_10"} 16108
telemt_desync_frames_bucket_total{bucket="gt_10"} 16160
telemt_pool_swap_total 222
telemt_pool_force_close_total 5783
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 692
telemt_me_draining_writers_reap_progress_total 76979
telemt_me_writer_removed_unexpected_total 2649
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7306
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 72430
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5311
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 472
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 71196
telemt_me_writer_teardown_success_total{mode="normal"} 79736
telemt_me_writer_teardown_noop_total 76984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 153947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 155779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 156335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 156670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 156720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 156720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 156720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 156720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 156720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 156720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 156720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 156720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 156720
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.107043
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 156720
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 692
telemt_me_refill_failed_total 443
telemt_me_writer_restored_same_endpoint_total 2240
telemt_me_writer_restored_fallback_total 149
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 9274539
telemt_user_connections_current{user="hello"} 1517
telemt_user_octets_from_client{user="hello"} 160844799788 (149.80 GB)
telemt_user_octets_to_client{user="hello"} 3630001578250 (3.30 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 190
```