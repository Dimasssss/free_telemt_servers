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

# Server Metrics 2026-03-17 19:14:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 88179.4 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1085904
telemt_connections_bad_total 7835
telemt_handshake_timeouts_total 29881
telemt_upstream_connect_attempt_total 20433
telemt_upstream_connect_success_total 19946
telemt_upstream_connect_fail_total 487
telemt_upstream_connect_attempts_per_request{bucket="1"} 20433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 487
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30371
telemt_me_reconnect_success_total 13244
telemt_me_reader_eof_total 14409
telemt_me_idle_close_by_peer_total 14408
telemt_me_route_drop_no_conn_total 491471
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993983
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6535
telemt_desync_full_logged_total 1866
telemt_desync_suppressed_total 4669
telemt_desync_frames_bucket_total{bucket="1_2"} 1781
telemt_desync_frames_bucket_total{bucket="3_10"} 2506
telemt_desync_frames_bucket_total{bucket="gt_10"} 2248
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 13973
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13222
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 988231
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 15014749331 (13.98 GB)
telemt_user_octets_to_client{user="hello"} 344788690147 (321.11 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 88431.3 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1063595
telemt_connections_bad_total 56214
telemt_handshake_timeouts_total 36339
telemt_upstream_connect_attempt_total 456093
telemt_upstream_connect_success_total 455224
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 456093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56926
telemt_me_reconnect_success_total 13777
telemt_me_reader_eof_total 15688
telemt_me_idle_close_by_peer_total 15688
telemt_me_route_drop_no_conn_total 260316
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475904
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1846
telemt_desync_full_logged_total 592
telemt_desync_suppressed_total 1254
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 773
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 15290
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13761
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1513
telemt_user_connections_total{user="hello"} 912348
telemt_user_connections_current{user="hello"} 1612
telemt_user_octets_from_client{user="hello"} 12556139470 (11.69 GB)
telemt_user_octets_to_client{user="hello"} 262546558870 (244.52 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 88207.1 (24h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553204
telemt_connections_bad_total 19302
telemt_handshake_timeouts_total 21749
telemt_upstream_connect_attempt_total 21551
telemt_upstream_connect_success_total 21429
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 21551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37648
telemt_me_reconnect_success_total 16978
telemt_me_reader_eof_total 18559
telemt_me_idle_close_by_peer_total 18552
telemt_me_route_drop_no_conn_total 249020
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 484912
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1373
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 968
telemt_desync_frames_bucket_total{bucket="1_2"} 414
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 17853
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16966
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 483129
telemt_user_connections_current{user="hello"} 1202
telemt_user_octets_from_client{user="hello"} 27165094924 (25.30 GB)
telemt_user_octets_to_client{user="hello"} 186014132948 (173.24 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 88266.3 (24h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1048876
telemt_connections_bad_total 26011
telemt_handshake_timeouts_total 20208
telemt_upstream_connect_attempt_total 81238
telemt_upstream_connect_success_total 80835
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 81238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33334
telemt_me_reconnect_success_total 13031
telemt_me_reader_eof_total 14379
telemt_me_idle_close_by_peer_total 14378
telemt_me_route_drop_no_conn_total 435615
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 848041
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2778
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 1876
telemt_desync_frames_bucket_total{bucket="1_2"} 663
telemt_desync_frames_bucket_total{bucket="3_10"} 1213
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13904
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13022
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 873
telemt_user_connections_total{user="hello"} 911107
telemt_user_connections_current{user="hello"} 1401
telemt_user_octets_from_client{user="hello"} 12953529759 (12.06 GB)
telemt_user_octets_to_client{user="hello"} 341524057757 (318.07 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 88238.1 (24h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609044
telemt_connections_bad_total 75864
telemt_handshake_timeouts_total 5202
telemt_upstream_connect_attempt_total 39857
telemt_upstream_connect_success_total 39330
telemt_upstream_connect_fail_total 527
telemt_upstream_connect_attempts_per_request{bucket="1"} 39857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 527
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50907
telemt_me_reconnect_success_total 18425
telemt_me_reader_eof_total 20092
telemt_me_idle_close_by_peer_total 20090
telemt_me_route_drop_no_conn_total 187875
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477206
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2154
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1582
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 42
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19755
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18417
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1330
telemt_user_connections_total{user="hello"} 493861
telemt_user_connections_current{user="hello"} 1345
telemt_user_octets_from_client{user="hello"} 9435655384 (8.79 GB)
telemt_user_octets_to_client{user="hello"} 230004209392 (214.21 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 88400.7 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 904643
telemt_connections_bad_total 61511
telemt_handshake_timeouts_total 8882
telemt_upstream_connect_attempt_total 17612
telemt_upstream_connect_success_total 17513
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9059
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24337
telemt_me_reconnect_success_total 13063
telemt_me_reader_eof_total 14206
telemt_me_idle_close_by_peer_total 14204
telemt_me_route_drop_no_conn_total 652920
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 920745
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1795
telemt_desync_full_logged_total 618
telemt_desync_suppressed_total 1177
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 672
telemt_pool_swap_total 73
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13636
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13049
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 573
telemt_user_connections_total{user="hello"} 783788
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 12045387120 (11.22 GB)
telemt_user_octets_to_client{user="hello"} 338940105996 (315.66 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 36166.5 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232154
telemt_connections_bad_total 29642
telemt_handshake_timeouts_total 6087
telemt_upstream_connect_attempt_total 15773
telemt_upstream_connect_success_total 15635
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 15773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25211
telemt_me_reconnect_success_total 13624
telemt_me_reader_eof_total 14411
telemt_me_idle_close_by_peer_total 14411
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 55573
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179045
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 555
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14150
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13599
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 178985
telemt_user_connections_current{user="hello"} 905
telemt_user_octets_from_client{user="hello"} 17260674537 (16.08 GB)
telemt_user_octets_to_client{user="hello"} 153862744534 (143.30 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 84
```