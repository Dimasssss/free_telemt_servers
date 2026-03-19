# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
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

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
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

# Server Metrics 2026-03-19 12:06:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 51486.5 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1266255
telemt_connections_bad_total 103967
telemt_connections_current 1655
telemt_connections_me_current 1655
telemt_handshake_timeouts_total 44996
telemt_upstream_connect_attempt_total 9886
telemt_upstream_connect_success_total 9717
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 9886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 8999
telemt_me_reconnect_success_total 7106
telemt_me_reader_eof_total 7518
telemt_me_idle_close_by_peer_total 7515
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 524944
telemt_me_route_drop_channel_closed_total 211
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 994476
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5535
telemt_desync_full_logged_total 1693
telemt_desync_suppressed_total 3842
telemt_desync_frames_bucket_total{bucket="1_2"} 1767
telemt_desync_frames_bucket_total{bucket="3_10"} 2003
telemt_desync_frames_bucket_total{bucket="gt_10"} 1765
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7269
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 7085
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 988378
telemt_user_connections_current{user="hello"} 1655
telemt_user_octets_from_client{user="hello"} 15436961032 (14.38 GB)
telemt_user_octets_to_client{user="hello"} 298396879400 (277.90 GB)
telemt_user_unique_ips_current{user="hello"} 571
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 51490.9 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3601325
telemt_connections_bad_total 231474
telemt_connections_current 3993
telemt_connections_me_current 3993
telemt_handshake_timeouts_total 63438
telemt_upstream_connect_attempt_total 9665
telemt_upstream_connect_success_total 9483
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 9665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 17366
telemt_me_reconnect_success_total 6838
telemt_me_reader_eof_total 7480
telemt_me_idle_close_by_peer_total 7479
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 3076316
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3038127
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11611
telemt_desync_full_logged_total 3891
telemt_desync_suppressed_total 7720
telemt_desync_frames_bucket_total{bucket="1_2"} 2262
telemt_desync_frames_bucket_total{bucket="3_10"} 4560
telemt_desync_frames_bucket_total{bucket="gt_10"} 4789
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7287
telemt_me_refill_failed_total 328
telemt_me_writer_restored_same_endpoint_total 6815
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 3037721
telemt_user_connections_current{user="hello"} 3993
telemt_user_octets_from_client{user="hello"} 37920075396 (35.32 GB)
telemt_user_octets_to_client{user="hello"} 857961443524 (799.04 GB)
telemt_user_unique_ips_current{user="hello"} 1313
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 51488.6 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2703829
telemt_connections_bad_total 312650
telemt_connections_current 3181
telemt_connections_me_current 3181
telemt_handshake_timeouts_total 53095
telemt_upstream_connect_attempt_total 9372
telemt_upstream_connect_success_total 9372
telemt_upstream_connect_attempts_per_request{bucket="1"} 9372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 8983
telemt_me_reconnect_success_total 6725
telemt_me_reader_eof_total 7156
telemt_me_idle_close_by_peer_total 7154
telemt_me_route_drop_no_conn_total 1741916
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2135318
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8685
telemt_desync_full_logged_total 2753
telemt_desync_suppressed_total 5932
telemt_desync_frames_bucket_total{bucket="1_2"} 1969
telemt_desync_frames_bucket_total{bucket="3_10"} 3179
telemt_desync_frames_bucket_total{bucket="gt_10"} 3537
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6909
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 6709
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 2132992
telemt_user_connections_current{user="hello"} 3181
telemt_user_octets_from_client{user="hello"} 29091187300 (27.09 GB)
telemt_user_octets_to_client{user="hello"} 891687033964 (830.45 GB)
telemt_user_unique_ips_current{user="hello"} 1114
telemt_user_unique_ips_recent_window{user="hello"} 592
```

## landvps.ru

Не удалось получить метрики для этого сервера.

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 51485.4 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3325115
telemt_connections_bad_total 709216
telemt_connections_current 4098
telemt_connections_me_current 4098
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 64585
telemt_upstream_connect_attempt_total 60994
telemt_upstream_connect_success_total 58517
telemt_upstream_connect_fail_total 2477
telemt_upstream_connect_attempts_per_request{bucket="1"} 60994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1011
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2477
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 69697
telemt_me_reconnect_success_total 6745
telemt_me_reader_eof_total 7070
telemt_me_idle_close_by_peer_total 7067
telemt_me_route_drop_no_conn_total 1412393
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2177172
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9196
telemt_desync_full_logged_total 2862
telemt_desync_suppressed_total 6334
telemt_desync_frames_bucket_total{bucket="1_2"} 1740
telemt_desync_frames_bucket_total{bucket="3_10"} 3969
telemt_desync_frames_bucket_total{bucket="gt_10"} 3487
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6830
telemt_me_refill_failed_total 1964
telemt_me_writer_restored_same_endpoint_total 6721
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 2226247
telemt_user_connections_current{user="hello"} 4098
telemt_user_octets_from_client{user="hello"} 36372770003 (33.87 GB)
telemt_user_octets_to_client{user="hello"} 835692556192 (778.30 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1189
telemt_user_unique_ips_recent_window{user="hello"} 785
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 51497.2 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555166
telemt_connections_bad_total 19002
telemt_connections_current 1154
telemt_connections_me_current 1154
telemt_handshake_timeouts_total 4346
telemt_upstream_connect_attempt_total 12695
telemt_upstream_connect_success_total 12361
telemt_upstream_connect_fail_total 333
telemt_upstream_connect_attempts_per_request{bucket="1"} 12694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 333
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 17340
telemt_me_reconnect_success_total 9747
telemt_me_reader_eof_total 10386
telemt_me_idle_close_by_peer_total 10386
telemt_me_route_drop_no_conn_total 289559
telemt_me_route_drop_channel_closed_total 38
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504933
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1192
telemt_desync_full_logged_total 411
telemt_desync_suppressed_total 781
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 10076
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9716
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 504865
telemt_user_connections_current{user="hello"} 1154
telemt_user_octets_from_client{user="hello"} 8226139180 (7.66 GB)
telemt_user_octets_to_client{user="hello"} 182471740488 (169.94 GB)
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 51487.3 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2243012
telemt_connections_bad_total 180074
telemt_connections_current 3249
telemt_connections_me_current 3249
telemt_handshake_timeouts_total 73671
telemt_upstream_connect_attempt_total 10414
telemt_upstream_connect_success_total 10413
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 9815
telemt_me_reconnect_success_total 7771
telemt_me_reader_eof_total 8231
telemt_me_idle_close_by_peer_total 8230
telemt_me_route_drop_no_conn_total 1161591
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1884481
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10229
telemt_desync_full_logged_total 3271
telemt_desync_suppressed_total 6958
telemt_desync_frames_bucket_total{bucket="1_2"} 1957
telemt_desync_frames_bucket_total{bucket="3_10"} 3890
telemt_desync_frames_bucket_total{bucket="gt_10"} 4382
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7935
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 7756
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 1883236
telemt_user_connections_current{user="hello"} 3249
telemt_user_octets_from_client{user="hello"} 24543210832 (22.86 GB)
telemt_user_octets_to_client{user="hello"} 830898287428 (773.83 GB)
telemt_user_unique_ips_current{user="hello"} 1033
telemt_user_unique_ips_recent_window{user="hello"} 484
```