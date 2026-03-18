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

# Server Metrics 2026-03-18 08:34:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 1879.8 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80629
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 979
telemt_upstream_connect_attempt_total 17254
telemt_upstream_connect_success_total 16918
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 17254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 317524
telemt_me_reconnect_success_total 502
telemt_me_reader_eof_total 416
telemt_me_idle_close_by_peer_total 416
telemt_me_route_drop_no_conn_total 24991
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54454
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 29
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 211
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 415
telemt_me_refill_failed_total 9906
telemt_me_writer_restored_same_endpoint_total 499
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 14752
telemt_user_connections_total{user="hello"} 70746
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 806631475 (769.26 MB)
telemt_user_octets_to_client{user="hello"} 11962871790 (11.14 GB)
telemt_user_msgs_from_client{user="hello"} 160740
telemt_user_msgs_to_client{user="hello"} 206050
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 136427.3 (37h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2142955
telemt_connections_bad_total 116701
telemt_handshake_timeouts_total 63880
telemt_upstream_connect_attempt_total 472891
telemt_upstream_connect_success_total 471227
telemt_upstream_connect_fail_total 1664
telemt_upstream_connect_attempts_per_request{bucket="1"} 472891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1664
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 137592
telemt_me_reconnect_success_total 21509
telemt_me_reader_eof_total 24118
telemt_me_idle_close_by_peer_total 24104
telemt_me_route_drop_no_conn_total 714910
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1423651
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6343
telemt_desync_full_logged_total 2199
telemt_desync_suppressed_total 4144
telemt_desync_frames_bucket_total{bucket="1_2"} 1198
telemt_desync_frames_bucket_total{bucket="3_10"} 2557
telemt_desync_frames_bucket_total{bucket="gt_10"} 2588
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23444
telemt_me_refill_failed_total 3621
telemt_me_writer_restored_same_endpoint_total 21491
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1935
telemt_user_connections_total{user="hello"} 1866006
telemt_user_connections_current{user="hello"} 3278
telemt_user_octets_from_client{user="hello"} 31828794001 (29.64 GB)
telemt_user_octets_to_client{user="hello"} 737867363826 (687.19 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 1017
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 136262.5 (37h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2105350
telemt_connections_bad_total 96056
telemt_handshake_timeouts_total 40346
telemt_upstream_connect_attempt_total 93841
telemt_upstream_connect_success_total 91374
telemt_upstream_connect_fail_total 2467
telemt_upstream_connect_attempts_per_request{bucket="1"} 93841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 389
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2467
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 42254
telemt_me_reconnect_success_total 19788
telemt_me_reader_eof_total 21693
telemt_me_idle_close_by_peer_total 21690
telemt_me_route_drop_no_conn_total 1106409
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1759434
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6801
telemt_desync_full_logged_total 2074
telemt_desync_suppressed_total 4727
telemt_desync_frames_bucket_total{bucket="1_2"} 1509
telemt_desync_frames_bucket_total{bucket="3_10"} 2805
telemt_desync_frames_bucket_total{bucket="gt_10"} 2487
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 20860
telemt_me_refill_failed_total 692
telemt_me_writer_restored_same_endpoint_total 19768
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1072
telemt_user_connections_total{user="hello"} 1822506
telemt_user_connections_current{user="hello"} 3147
telemt_user_octets_from_client{user="hello"} 29550315654 (27.52 GB)
telemt_user_octets_to_client{user="hello"} 769562491098 (716.71 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 427
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 136234.4 (37h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1532393
telemt_connections_bad_total 130731
telemt_handshake_timeouts_total 19072
telemt_upstream_connect_attempt_total 50276
telemt_upstream_connect_success_total 49566
telemt_upstream_connect_fail_total 710
telemt_upstream_connect_attempts_per_request{bucket="1"} 50276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 434
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 710
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 71932
telemt_me_reconnect_success_total 26300
telemt_me_reader_eof_total 28711
telemt_me_idle_close_by_peer_total 28708
telemt_me_route_drop_no_conn_total 652902
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1271664
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5503
telemt_desync_full_logged_total 1692
telemt_desync_suppressed_total 3811
telemt_desync_frames_bucket_total{bucket="1_2"} 1373
telemt_desync_frames_bucket_total{bucket="3_10"} 2116
telemt_desync_frames_bucket_total{bucket="gt_10"} 2014
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 28131
telemt_me_refill_failed_total 1420
telemt_me_writer_restored_same_endpoint_total 26292
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1831
telemt_user_connections_total{user="hello"} 1287880
telemt_user_connections_current{user="hello"} 2624
telemt_user_octets_from_client{user="hello"} 24577967704 (22.89 GB)
telemt_user_octets_to_client{user="hello"} 607495107892 (565.77 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 793
telemt_user_unique_ips_recent_window{user="hello"} 396
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 136395.9 (37h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1382847
telemt_connections_bad_total 146285
telemt_handshake_timeouts_total 11329
telemt_upstream_connect_attempt_total 27231
telemt_upstream_connect_success_total 27070
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 27231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 293
telemt_me_reconnect_attempts_total 31599
telemt_me_reconnect_success_total 20282
telemt_me_reader_eof_total 21922
telemt_me_idle_close_by_peer_total 21919
telemt_me_route_drop_no_conn_total 941361
telemt_me_route_drop_channel_closed_total 103
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1334451
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2629
telemt_desync_full_logged_total 922
telemt_desync_suppressed_total 1707
telemt_desync_frames_bucket_total{bucket="1_2"} 566
telemt_desync_frames_bucket_total{bucket="3_10"} 1015
telemt_desync_frames_bucket_total{bucket="gt_10"} 1048
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20947
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 20268
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 665
telemt_user_connections_total{user="hello"} 1143095
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 17304548116 (16.12 GB)
telemt_user_octets_to_client{user="hello"} 481122484116 (448.08 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 84162.7 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 883456
telemt_connections_bad_total 81911
telemt_handshake_timeouts_total 18380
telemt_upstream_connect_attempt_total 27687
telemt_upstream_connect_success_total 27366
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 27687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 38310
telemt_me_reconnect_success_total 23017
telemt_me_reader_eof_total 24372
telemt_me_idle_close_by_peer_total 24372
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 285116
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 676486
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2650
telemt_desync_full_logged_total 907
telemt_desync_suppressed_total 1743
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 1076
telemt_desync_frames_bucket_total{bucket="gt_10"} 1121
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23750
telemt_me_refill_failed_total 473
telemt_me_writer_restored_same_endpoint_total 22970
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 733
telemt_user_connections_total{user="hello"} 676107
telemt_user_connections_current{user="hello"} 1863
telemt_user_octets_from_client{user="hello"} 31016690897 (28.89 GB)
telemt_user_octets_to_client{user="hello"} 465178257986 (433.23 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 250
```