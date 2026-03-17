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

# Server Metrics 2026-03-17 10:03:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 55087.5 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446046
telemt_connections_bad_total 3738
telemt_handshake_timeouts_total 12585
telemt_upstream_connect_attempt_total 13964
telemt_upstream_connect_success_total 13531
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 13964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 10001
telemt_me_reconnect_success_total 8474
telemt_me_reader_eof_total 9004
telemt_me_idle_close_by_peer_total 9003
telemt_me_route_drop_no_conn_total 141328
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403138
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3271
telemt_desync_full_logged_total 869
telemt_desync_suppressed_total 2402
telemt_desync_frames_bucket_total{bucket="1_2"} 865
telemt_desync_frames_bucket_total{bucket="3_10"} 1410
telemt_desync_frames_bucket_total{bucket="gt_10"} 996
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 8647
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8452
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 405105
telemt_user_connections_current{user="hello"} 1039
telemt_user_octets_from_client{user="hello"} 5874186947 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 158843660031 (147.93 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 55339.0 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242517
telemt_connections_bad_total 2663
telemt_handshake_timeouts_total 14175
telemt_upstream_connect_attempt_total 14281
telemt_upstream_connect_success_total 14085
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 14281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 20048
telemt_me_reconnect_success_total 11338
telemt_me_reader_eof_total 12177
telemt_me_idle_close_by_peer_total 12177
telemt_me_route_drop_no_conn_total 88109
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213589
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 568
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 353
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11726
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11322
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 213590
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 2619330244 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 81273603388 (75.69 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 55114.8 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148756
telemt_connections_bad_total 7598
telemt_handshake_timeouts_total 10767
telemt_upstream_connect_attempt_total 14676
telemt_upstream_connect_success_total 14598
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 14676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12772
telemt_me_reconnect_success_total 11803
telemt_me_reader_eof_total 12604
telemt_me_idle_close_by_peer_total 12604
telemt_me_route_drop_no_conn_total 44868
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120847
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 380
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11991
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11792
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 120767
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 9368066944 (8.72 GB)
telemt_user_octets_to_client{user="hello"} 37442898308 (34.87 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 55174.0 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329462
telemt_connections_bad_total 6193
telemt_handshake_timeouts_total 11352
telemt_upstream_connect_attempt_total 12668
telemt_upstream_connect_success_total 12549
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 12668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10810
telemt_me_reconnect_success_total 9718
telemt_me_reader_eof_total 10332
telemt_me_idle_close_by_peer_total 10332
telemt_me_route_drop_no_conn_total 92396
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266999
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 591
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9903
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9710
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 266954
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 3070022502 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 105362278097 (98.13 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 55145.9 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183122
telemt_connections_bad_total 50272
telemt_handshake_timeouts_total 2823
telemt_upstream_connect_attempt_total 16836
telemt_upstream_connect_success_total 16616
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 16836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_reconnect_attempts_total 20849
telemt_me_reconnect_success_total 13726
telemt_me_reader_eof_total 14543
telemt_me_idle_close_by_peer_total 14543
telemt_me_route_drop_no_conn_total 47658
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124546
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 413
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 14121
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13718
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 395
telemt_user_connections_total{user="hello"} 124571
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 1873246739 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 56408185322 (52.53 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 55307.0 (15h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426575
telemt_connections_bad_total 48893
telemt_handshake_timeouts_total 4339
telemt_upstream_connect_attempt_total 11264
telemt_upstream_connect_success_total 11202
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5673
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 12327
telemt_me_reconnect_success_total 8443
telemt_me_reader_eof_total 9119
telemt_me_idle_close_by_peer_total 9119
telemt_me_route_drop_no_conn_total 280137
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428544
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 375
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 8693
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8429
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 350425
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 5066881760 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 191739570696 (178.57 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 3074.1 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2906
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 1269
telemt_upstream_connect_success_total 1245
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 954
telemt_me_reconnect_success_total 924
telemt_me_reader_eof_total 967
telemt_me_idle_close_by_peer_total 967
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 974
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2656
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 939
telemt_me_writer_restored_same_endpoint_total 918
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 2762
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 37281521 (35.55 MB)
telemt_user_octets_to_client{user="hello"} 10747101326 (10.01 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```