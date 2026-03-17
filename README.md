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

# Server Metrics 2026-03-17 18:59:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 87262.5 (24h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1069594
telemt_connections_bad_total 7522
telemt_handshake_timeouts_total 29503
telemt_upstream_connect_attempt_total 20288
telemt_upstream_connect_success_total 19803
telemt_upstream_connect_fail_total 485
telemt_upstream_connect_attempts_per_request{bucket="1"} 20288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 485
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 30270
telemt_me_reconnect_success_total 13147
telemt_me_reader_eof_total 14302
telemt_me_idle_close_by_peer_total 14301
telemt_me_route_drop_no_conn_total 484874
telemt_me_route_drop_channel_closed_total 140
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 978953
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6411
telemt_desync_full_logged_total 1835
telemt_desync_suppressed_total 4576
telemt_desync_frames_bucket_total{bucket="1_2"} 1761
telemt_desync_frames_bucket_total{bucket="3_10"} 2458
telemt_desync_frames_bucket_total{bucket="gt_10"} 2192
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13872
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13125
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 973194
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 14858194843 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 340059890387 (316.71 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 87514.1 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1037885
telemt_connections_bad_total 55863
telemt_handshake_timeouts_total 35289
telemt_upstream_connect_attempt_total 455953
telemt_upstream_connect_success_total 455084
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 455953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56829
telemt_me_reconnect_success_total 13680
telemt_me_reader_eof_total 15585
telemt_me_idle_close_by_peer_total 15585
telemt_me_route_drop_no_conn_total 252532
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454812
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1718
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1167
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 728
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 15192
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13664
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1512
telemt_user_connections_total{user="hello"} 891329
telemt_user_connections_current{user="hello"} 1511
telemt_user_octets_from_client{user="hello"} 12175075186 (11.34 GB)
telemt_user_octets_to_client{user="hello"} 243042471598 (226.35 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 87289.9 (24h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537564
telemt_connections_bad_total 19052
telemt_handshake_timeouts_total 21621
telemt_upstream_connect_attempt_total 21402
telemt_upstream_connect_success_total 21284
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 37546
telemt_me_reconnect_success_total 16876
telemt_me_reader_eof_total 18452
telemt_me_idle_close_by_peer_total 18445
telemt_me_route_drop_no_conn_total 242643
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470403
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1288
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 902
telemt_desync_frames_bucket_total{bucket="1_2"} 399
telemt_desync_frames_bucket_total{bucket="3_10"} 538
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 17750
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16864
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 874
telemt_user_connections_total{user="hello"} 468572
telemt_user_connections_current{user="hello"} 1161
telemt_user_octets_from_client{user="hello"} 26915697872 (25.07 GB)
telemt_user_octets_to_client{user="hello"} 177950426752 (165.73 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 87349.3 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028272
telemt_connections_bad_total 24912
telemt_handshake_timeouts_total 19833
telemt_upstream_connect_attempt_total 81093
telemt_upstream_connect_success_total 80691
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 81093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11237
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33245
telemt_me_reconnect_success_total 12943
telemt_me_reader_eof_total 14284
telemt_me_idle_close_by_peer_total 14283
telemt_me_route_drop_no_conn_total 428117
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 829768
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2702
telemt_desync_full_logged_total 873
telemt_desync_suppressed_total 1829
telemt_desync_frames_bucket_total{bucket="1_2"} 644
telemt_desync_frames_bucket_total{bucket="3_10"} 1176
telemt_desync_frames_bucket_total{bucket="gt_10"} 882
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13814
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12934
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 871
telemt_user_connections_total{user="hello"} 892835
telemt_user_connections_current{user="hello"} 1444
telemt_user_octets_from_client{user="hello"} 12641242211 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 329239234525 (306.63 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 87321.2 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592931
telemt_connections_bad_total 75695
telemt_handshake_timeouts_total 5103
telemt_upstream_connect_attempt_total 39691
telemt_upstream_connect_success_total 39168
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 39691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50797
telemt_me_reconnect_success_total 18316
telemt_me_reader_eof_total 19973
telemt_me_idle_close_by_peer_total 19971
telemt_me_route_drop_no_conn_total 180388
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461886
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2103
telemt_desync_full_logged_total 546
telemt_desync_suppressed_total 1557
telemt_desync_frames_bucket_total{bucket="1_2"} 767
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 516
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19643
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18308
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1327
telemt_user_connections_total{user="hello"} 478546
telemt_user_connections_current{user="hello"} 1291
telemt_user_octets_from_client{user="hello"} 8601394340 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 221742229000 (206.51 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 87482.7 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 894801
telemt_connections_bad_total 61443
telemt_handshake_timeouts_total 8862
telemt_upstream_connect_attempt_total 17454
telemt_upstream_connect_success_total 17355
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24222
telemt_me_reconnect_success_total 12949
telemt_me_reader_eof_total 14085
telemt_me_idle_close_by_peer_total 14083
telemt_me_route_drop_no_conn_total 648459
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 911488
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1761
telemt_desync_full_logged_total 606
telemt_desync_suppressed_total 1155
telemt_desync_frames_bucket_total{bucket="1_2"} 421
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 663
telemt_pool_swap_total 72
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13521
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12935
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 774535
telemt_user_connections_current{user="hello"} 800
telemt_user_octets_from_client{user="hello"} 11830263488 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 334736303660 (311.75 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 35249.4 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214031
telemt_connections_bad_total 23048
telemt_handshake_timeouts_total 5948
telemt_upstream_connect_attempt_total 15502
telemt_upstream_connect_success_total 15367
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 15502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24987
telemt_me_reconnect_success_total 13404
telemt_me_reader_eof_total 14188
telemt_me_idle_close_by_peer_total 14188
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 51789
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168774
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 473
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13925
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13380
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 168718
telemt_user_connections_current{user="hello"} 949
telemt_user_octets_from_client{user="hello"} 14949277029 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 147757426834 (137.61 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 97
```