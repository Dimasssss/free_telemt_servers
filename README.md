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

# Server Metrics 2026-03-17 15:30:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 74716.4 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823770
telemt_connections_bad_total 6103
telemt_handshake_timeouts_total 24129
telemt_upstream_connect_attempt_total 17742
telemt_upstream_connect_success_total 17281
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 17742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 130
telemt_me_reconnect_attempts_total 25955
telemt_me_reconnect_success_total 11251
telemt_me_reader_eof_total 12265
telemt_me_idle_close_by_peer_total 12264
telemt_me_route_drop_no_conn_total 345000
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 748535
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5192
telemt_desync_full_logged_total 1442
telemt_desync_suppressed_total 3750
telemt_desync_frames_bucket_total{bucket="1_2"} 1500
telemt_desync_frames_bucket_total{bucket="3_10"} 2054
telemt_desync_frames_bucket_total{bucket="gt_10"} 1638
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11863
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11229
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 750371
telemt_user_connections_current{user="hello"} 1010
telemt_user_octets_from_client{user="hello"} 12044119699 (11.22 GB)
telemt_user_octets_to_client{user="hello"} 248698005983 (231.62 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 74967.8 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 541233
telemt_connections_bad_total 31848
telemt_handshake_timeouts_total 28126
telemt_upstream_connect_attempt_total 103520
telemt_upstream_connect_success_total 102977
telemt_upstream_connect_fail_total 541
telemt_upstream_connect_attempts_per_request{bucket="1"} 103518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13023
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7487
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 541
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 40104
telemt_me_reconnect_success_total 13469
telemt_me_reader_eof_total 14855
telemt_me_idle_close_by_peer_total 14855
telemt_me_route_drop_no_conn_total 194135
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370594
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 1014
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14464
telemt_me_refill_failed_total 828
telemt_me_writer_restored_same_endpoint_total 13453
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 995
telemt_user_connections_total{user="hello"} 456224
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 5066932088 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 131129408369 (122.12 GB)
telemt_user_msgs_from_client{user="hello"} 1257041
telemt_user_msgs_to_client{user="hello"} 4423297
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 74743.7 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276909
telemt_connections_bad_total 7838
telemt_handshake_timeouts_total 18560
telemt_upstream_connect_attempt_total 19501
telemt_upstream_connect_success_total 19399
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 19501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 29395
telemt_me_reconnect_success_total 15605
telemt_me_reader_eof_total 16900
telemt_me_idle_close_by_peer_total 16897
telemt_me_route_drop_no_conn_total 129989
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16245
telemt_me_refill_failed_total 428
telemt_me_writer_restored_same_endpoint_total 15594
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 236212
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 18365090436 (17.10 GB)
telemt_user_octets_to_client{user="hello"} 58065826264 (54.08 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 74803.0 (20h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 643423
telemt_connections_bad_total 8670
telemt_handshake_timeouts_total 13807
telemt_upstream_connect_attempt_total 30695
telemt_upstream_connect_success_total 30477
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 30695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8678
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 28113
telemt_me_reconnect_success_total 11954
telemt_me_reader_eof_total 13108
telemt_me_idle_close_by_peer_total 13107
telemt_me_route_drop_no_conn_total 253219
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 540973
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1864
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 836
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12667
telemt_me_refill_failed_total 500
telemt_me_writer_restored_same_endpoint_total 11945
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 713
telemt_user_connections_total{user="hello"} 555503
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 6721537708 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 170268371936 (158.57 GB)
telemt_user_msgs_from_client{user="hello"} 135811
telemt_user_msgs_to_client{user="hello"} 691641
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 74774.9 (20h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296851
telemt_connections_bad_total 57585
telemt_handshake_timeouts_total 3709
telemt_upstream_connect_attempt_total 21475
telemt_upstream_connect_success_total 21001
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 21475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 42688
telemt_me_reconnect_success_total 16840
telemt_me_reader_eof_total 18237
telemt_me_idle_close_by_peer_total 18235
telemt_me_route_drop_no_conn_total 84374
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223082
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17927
telemt_me_refill_failed_total 803
telemt_me_writer_restored_same_endpoint_total 16832
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1087
telemt_user_connections_total{user="hello"} 223612
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 2769538367 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 83582806299 (77.84 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 74939.0 (20h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721767
telemt_connections_bad_total 58254
telemt_handshake_timeouts_total 7036
telemt_upstream_connect_attempt_total 15117
telemt_upstream_connect_success_total 15035
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21548
telemt_me_reconnect_success_total 11251
telemt_me_reader_eof_total 12243
telemt_me_idle_close_by_peer_total 12243
telemt_me_route_drop_no_conn_total 525636
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 732633
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1082
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 698
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 435
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11750
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11237
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 620021
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 9103634944 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 277007336124 (257.98 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 22703.1 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17638
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 312
telemt_upstream_connect_attempt_total 12219
telemt_upstream_connect_success_total 12115
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 12218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 22338
telemt_me_reconnect_success_total 10776
telemt_me_reader_eof_total 11419
telemt_me_idle_close_by_peer_total 11419
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 6480
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16797
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 11249
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 10761
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 16894
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 538243385 (513.31 MB)
telemt_user_octets_to_client{user="hello"} 23980241730 (22.33 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 8
```