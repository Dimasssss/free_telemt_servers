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

# Server Metrics 2026-03-17 16:47:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 79308.2 (22h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 928572
telemt_connections_bad_total 6486
telemt_handshake_timeouts_total 26159
telemt_upstream_connect_attempt_total 18847
telemt_upstream_connect_success_total 18373
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 18847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29186
telemt_me_reconnect_success_total 12071
telemt_me_reader_eof_total 13179
telemt_me_idle_close_by_peer_total 13178
telemt_me_route_drop_no_conn_total 430866
telemt_me_route_drop_channel_closed_total 114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 853540
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5695
telemt_desync_full_logged_total 1593
telemt_desync_suppressed_total 4102
telemt_desync_frames_bucket_total{bucket="1_2"} 1612
telemt_desync_frames_bucket_total{bucket="3_10"} 2211
telemt_desync_frames_bucket_total{bucket="gt_10"} 1872
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12773
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12049
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 702
telemt_user_connections_total{user="hello"} 847824
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 13199190915 (12.29 GB)
telemt_user_octets_to_client{user="hello"} 283252893875 (263.80 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 79560.7 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681150
telemt_connections_bad_total 39995
telemt_handshake_timeouts_total 29382
telemt_upstream_connect_attempt_total 210005
telemt_upstream_connect_success_total 209367
telemt_upstream_connect_fail_total 635
telemt_upstream_connect_attempts_per_request{bucket="1"} 210002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 173020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17744
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 635
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 47072
telemt_me_reconnect_success_total 13555
telemt_me_reader_eof_total 15154
telemt_me_idle_close_by_peer_total 15154
telemt_me_route_drop_no_conn_total 207556
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1507
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1033
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14765
telemt_me_refill_failed_total 1043
telemt_me_writer_restored_same_endpoint_total 13539
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1210
telemt_user_connections_total{user="hello"} 581878
telemt_user_connections_current{user="hello"} 2224
telemt_user_octets_from_client{user="hello"} 7163375454 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 158477397774 (147.59 GB)
telemt_user_msgs_from_client{user="hello"} 2966647
telemt_user_msgs_to_client{user="hello"} 11950774
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 363
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 79336.4 (22h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339801
telemt_connections_bad_total 9135
telemt_handshake_timeouts_total 19808
telemt_upstream_connect_attempt_total 20168
telemt_upstream_connect_success_total 20057
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 36668
telemt_me_reconnect_success_total 16001
telemt_me_reader_eof_total 17513
telemt_me_idle_close_by_peer_total 17510
telemt_me_route_drop_no_conn_total 176771
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295251
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 903
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 632
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 16858
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 15989
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 857
telemt_user_connections_total{user="hello"} 293439
telemt_user_connections_current{user="hello"} 1657
telemt_user_octets_from_client{user="hello"} 21812553208 (20.31 GB)
telemt_user_octets_to_client{user="hello"} 85004720100 (79.17 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 79395.4 (22h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 772402
telemt_connections_bad_total 13485
telemt_handshake_timeouts_total 15287
telemt_upstream_connect_attempt_total 79984
telemt_upstream_connect_success_total 79592
telemt_upstream_connect_fail_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 79984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 392
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 32503
telemt_me_reconnect_success_total 12209
telemt_me_reader_eof_total 13496
telemt_me_idle_close_by_peer_total 13495
telemt_me_route_drop_no_conn_total 285084
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 607825
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1998
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1331
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 900
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13055
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12200
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 846
telemt_user_connections_total{user="hello"} 670963
telemt_user_connections_current{user="hello"} 2140
telemt_user_octets_from_client{user="hello"} 8245245363 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 206776888861 (192.58 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 79367.1 (22h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372534
telemt_connections_bad_total 65851
telemt_handshake_timeouts_total 4060
telemt_upstream_connect_attempt_total 38203
telemt_upstream_connect_success_total 37707
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 38203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48500
telemt_me_reconnect_success_total 17208
telemt_me_reader_eof_total 18779
telemt_me_idle_close_by_peer_total 18777
telemt_me_route_drop_no_conn_total 104236
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270273
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1282
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 994
telemt_desync_frames_bucket_total{bucket="1_2"} 590
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18469
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17200
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1261
telemt_user_connections_total{user="hello"} 286994
telemt_user_connections_current{user="hello"} 1841
telemt_user_octets_from_client{user="hello"} 3759563728 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 114649311700 (106.78 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 79529.0 (22h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793509
telemt_connections_bad_total 60217
telemt_handshake_timeouts_total 7442
telemt_upstream_connect_attempt_total 16063
telemt_upstream_connect_success_total 15975
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 16063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 23230
telemt_me_reconnect_success_total 11964
telemt_me_reader_eof_total 13030
telemt_me_idle_close_by_peer_total 13028
telemt_me_route_drop_no_conn_total 594595
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 817082
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1343
telemt_desync_full_logged_total 473
telemt_desync_suppressed_total 870
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 527
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12513
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 11950
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 685405
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 9866350496 (9.19 GB)
telemt_user_octets_to_client{user="hello"} 305746946688 (284.75 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 27295.5 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51734
telemt_connections_bad_total 1747
telemt_handshake_timeouts_total 456
telemt_upstream_connect_attempt_total 13940
telemt_upstream_connect_success_total 13823
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 13940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23832
telemt_me_reconnect_success_total 12259
telemt_me_reader_eof_total 12980
telemt_me_idle_close_by_peer_total 12980
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 15846
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46879
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 12762
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12239
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 46879
telemt_user_connections_current{user="hello"} 1260
telemt_user_octets_from_client{user="hello"} 2489137809 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 55300701734 (51.50 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 131
```