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

# Server Metrics 2026-03-17 19:40:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 89709.8 (24h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1109480
telemt_connections_bad_total 7934
telemt_handshake_timeouts_total 30173
telemt_upstream_connect_attempt_total 20704
telemt_upstream_connect_success_total 20216
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30553
telemt_me_reconnect_success_total 13425
telemt_me_reader_eof_total 14603
telemt_me_idle_close_by_peer_total 14602
telemt_me_route_drop_no_conn_total 499873
telemt_me_route_drop_channel_closed_total 147
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015562
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6697
telemt_desync_full_logged_total 1918
telemt_desync_suppressed_total 4779
telemt_desync_frames_bucket_total{bucket="1_2"} 1806
telemt_desync_frames_bucket_total{bucket="3_10"} 2545
telemt_desync_frames_bucket_total{bucket="gt_10"} 2346
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14157
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13403
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 1009808
telemt_user_connections_current{user="hello"} 985
telemt_user_octets_from_client{user="hello"} 15285981907 (14.24 GB)
telemt_user_octets_to_client{user="hello"} 352800725531 (328.57 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 89961.1 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1098340
telemt_connections_bad_total 56692
telemt_handshake_timeouts_total 38530
telemt_upstream_connect_attempt_total 456289
telemt_upstream_connect_success_total 455416
telemt_upstream_connect_fail_total 873
telemt_upstream_connect_attempts_per_request{bucket="1"} 456289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 873
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57075
telemt_me_reconnect_success_total 13924
telemt_me_reader_eof_total 15846
telemt_me_idle_close_by_peer_total 15846
telemt_me_route_drop_no_conn_total 270955
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506896
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2054
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1402
telemt_desync_frames_bucket_total{bucket="1_2"} 430
telemt_desync_frames_bucket_total{bucket="3_10"} 869
telemt_desync_frames_bucket_total{bucket="gt_10"} 755
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 15441
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13908
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1517
telemt_user_connections_total{user="hello"} 943334
telemt_user_connections_current{user="hello"} 1545
telemt_user_octets_from_client{user="hello"} 13181498310 (12.28 GB)
telemt_user_octets_to_client{user="hello"} 287553178270 (267.80 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 89737.2 (24h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582378
telemt_connections_bad_total 23177
telemt_handshake_timeouts_total 21948
telemt_upstream_connect_attempt_total 21901
telemt_upstream_connect_success_total 21774
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 21901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37906
telemt_me_reconnect_success_total 17235
telemt_me_reader_eof_total 18822
telemt_me_idle_close_by_peer_total 18815
telemt_me_route_drop_no_conn_total 259949
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509103
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1481
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1047
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 596
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 18115
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17223
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 880
telemt_user_connections_total{user="hello"} 507383
telemt_user_connections_current{user="hello"} 1171
telemt_user_octets_from_client{user="hello"} 27609236492 (25.71 GB)
telemt_user_octets_to_client{user="hello"} 198799409036 (185.15 GB)
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 89796.5 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082293
telemt_connections_bad_total 27722
telemt_handshake_timeouts_total 20532
telemt_upstream_connect_attempt_total 81487
telemt_upstream_connect_success_total 81082
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 81487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33523
telemt_me_reconnect_success_total 13217
telemt_me_reader_eof_total 14582
telemt_me_idle_close_by_peer_total 14581
telemt_me_route_drop_no_conn_total 447190
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 877729
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2932
telemt_desync_full_logged_total 945
telemt_desync_suppressed_total 1987
telemt_desync_frames_bucket_total{bucket="1_2"} 698
telemt_desync_frames_bucket_total{bucket="3_10"} 1271
telemt_desync_frames_bucket_total{bucket="gt_10"} 963
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14096
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13208
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 879
telemt_user_connections_total{user="hello"} 940789
telemt_user_connections_current{user="hello"} 1350
telemt_user_octets_from_client{user="hello"} 13414799535 (12.49 GB)
telemt_user_octets_to_client{user="hello"} 358761434017 (334.12 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 89768.2 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634886
telemt_connections_bad_total 76991
telemt_handshake_timeouts_total 5422
telemt_upstream_connect_attempt_total 40144
telemt_upstream_connect_success_total 39611
telemt_upstream_connect_fail_total 533
telemt_upstream_connect_attempts_per_request{bucket="1"} 40144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 533
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51111
telemt_me_reconnect_success_total 18628
telemt_me_reader_eof_total 20311
telemt_me_idle_close_by_peer_total 20309
telemt_me_route_drop_no_conn_total 198021
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500452
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2268
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 1643
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 896
telemt_desync_frames_bucket_total{bucket="gt_10"} 569
telemt_pool_swap_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19961
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18620
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1333
telemt_user_connections_total{user="hello"} 517101
telemt_user_connections_current{user="hello"} 1250
telemt_user_octets_from_client{user="hello"} 10369435484 (9.66 GB)
telemt_user_octets_to_client{user="hello"} 240247483828 (223.75 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 89931.1 (24h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 921370
telemt_connections_bad_total 61567
telemt_handshake_timeouts_total 8936
telemt_upstream_connect_attempt_total 17841
telemt_upstream_connect_success_total 17741
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 17841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24522
telemt_me_reconnect_success_total 13247
telemt_me_reader_eof_total 14400
telemt_me_idle_close_by_peer_total 14398
telemt_me_route_drop_no_conn_total 660290
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935829
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1846
telemt_desync_full_logged_total 642
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 694
telemt_pool_swap_total 74
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13823
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13233
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 576
telemt_user_connections_total{user="hello"} 798869
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 12254881204 (11.41 GB)
telemt_user_octets_to_client{user="hello"} 346129264560 (322.36 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 37696.4 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250956
telemt_connections_bad_total 32907
telemt_handshake_timeouts_total 6437
telemt_upstream_connect_attempt_total 16208
telemt_upstream_connect_success_total 16065
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 16208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25598
telemt_me_reconnect_success_total 14011
telemt_me_reader_eof_total 14819
telemt_me_idle_close_by_peer_total 14819
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 60779
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192915
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 583
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14538
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13986
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 192855
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 18922137329 (17.62 GB)
telemt_user_octets_to_client{user="hello"} 161348029346 (150.27 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 74
```