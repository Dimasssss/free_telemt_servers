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

# Server Metrics 2026-03-17 23:29:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 103482.3 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1235567
telemt_connections_bad_total 9043
telemt_handshake_timeouts_total 32282
telemt_upstream_connect_attempt_total 23247
telemt_upstream_connect_success_total 22752
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 23247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32444
telemt_me_reconnect_success_total 15310
telemt_me_reader_eof_total 16628
telemt_me_idle_close_by_peer_total 16627
telemt_me_route_drop_no_conn_total 547655
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1134702
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7472
telemt_desync_full_logged_total 2175
telemt_desync_suppressed_total 5297
telemt_desync_frames_bucket_total{bucket="1_2"} 1998
telemt_desync_frames_bucket_total{bucket="3_10"} 2831
telemt_desync_frames_bucket_total{bucket="gt_10"} 2643
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 16069
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15288
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 759
telemt_user_connections_total{user="hello"} 1128925
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 21979879663 (20.47 GB)
telemt_user_octets_to_client{user="hello"} 408214249887 (380.18 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 103733.7 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1307981
telemt_connections_bad_total 60964
telemt_handshake_timeouts_total 45301
telemt_upstream_connect_attempt_total 458845
telemt_upstream_connect_success_total 457933
telemt_upstream_connect_fail_total 912
telemt_upstream_connect_attempts_per_request{bucket="1"} 458845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 912
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58900
telemt_me_reconnect_success_total 15742
telemt_me_reader_eof_total 17787
telemt_me_idle_close_by_peer_total 17787
telemt_me_route_drop_no_conn_total 340164
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 698989
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3203
telemt_desync_full_logged_total 1047
telemt_desync_suppressed_total 2156
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 1312
telemt_desync_frames_bucket_total{bucket="gt_10"} 1264
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17284
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15726
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 1135417
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 15613120894 (14.54 GB)
telemt_user_octets_to_client{user="hello"} 389487271194 (362.74 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 103509.9 (28h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 769956
telemt_connections_bad_total 48622
telemt_handshake_timeouts_total 23718
telemt_upstream_connect_attempt_total 24372
telemt_upstream_connect_success_total 24232
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 24372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39716
telemt_me_reconnect_success_total 19035
telemt_me_reader_eof_total 20745
telemt_me_idle_close_by_peer_total 20738
telemt_me_route_drop_no_conn_total 314485
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2132
telemt_desync_full_logged_total 693
telemt_desync_suppressed_total 1439
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 19942
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19023
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 907
telemt_user_connections_total{user="hello"} 652847
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 31725856808 (29.55 GB)
telemt_user_octets_to_client{user="hello"} 289107697692 (269.25 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 103569.4 (28h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1258452
telemt_connections_bad_total 48098
telemt_handshake_timeouts_total 21641
telemt_upstream_connect_attempt_total 83993
telemt_upstream_connect_success_total 83555
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 83992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35334
telemt_me_reconnect_success_total 15006
telemt_me_reader_eof_total 16523
telemt_me_idle_close_by_peer_total 16521
telemt_me_route_drop_no_conn_total 517940
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1027572
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3871
telemt_desync_full_logged_total 1274
telemt_desync_suppressed_total 2597
telemt_desync_frames_bucket_total{bucket="1_2"} 946
telemt_desync_frames_bucket_total{bucket="3_10"} 1623
telemt_desync_frames_bucket_total{bucket="gt_10"} 1302
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15919
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14997
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 913
telemt_user_connections_total{user="hello"} 1090056
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 17160873107 (15.98 GB)
telemt_user_octets_to_client{user="hello"} 497037983273 (462.90 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 103541.2 (28h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 815111
telemt_connections_bad_total 96116
telemt_handshake_timeouts_total 6587
telemt_upstream_connect_attempt_total 43192
telemt_upstream_connect_success_total 42604
telemt_upstream_connect_fail_total 588
telemt_upstream_connect_attempts_per_request{bucket="1"} 43192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 405
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 588
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55915
telemt_me_reconnect_success_total 20961
telemt_me_reader_eof_total 22820
telemt_me_idle_close_by_peer_total 22818
telemt_me_route_drop_no_conn_total 258924
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654621
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3088
telemt_desync_full_logged_total 908
telemt_desync_suppressed_total 2180
telemt_desync_frames_bucket_total{bucket="1_2"} 985
telemt_desync_frames_bucket_total{bucket="3_10"} 1232
telemt_desync_frames_bucket_total{bucket="gt_10"} 871
telemt_pool_swap_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22406
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20953
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1445
telemt_user_connections_total{user="hello"} 671231
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 13292350484 (12.38 GB)
telemt_user_octets_to_client{user="hello"} 332349176024 (309.52 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 103702.2 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1048454
telemt_connections_bad_total 93044
telemt_handshake_timeouts_total 9546
telemt_upstream_connect_attempt_total 20556
telemt_upstream_connect_success_total 20441
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26532
telemt_me_reconnect_success_total 15252
telemt_me_reader_eof_total 16562
telemt_me_idle_close_by_peer_total 16560
telemt_me_route_drop_no_conn_total 701667
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1016429
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 90
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15853
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15238
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 601
telemt_user_connections_total{user="hello"} 879455
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 14238830220 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 371280311660 (345.78 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 51469.5 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 374709
telemt_connections_bad_total 44615
telemt_handshake_timeouts_total 10706
telemt_upstream_connect_attempt_total 19579
telemt_upstream_connect_success_total 19400
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 19579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28245
telemt_me_reconnect_success_total 16648
telemt_me_reader_eof_total 17605
telemt_me_idle_close_by_peer_total 17605
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 94155
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281349
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1027
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 704
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 382
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17206
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16619
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 281287
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 21996589649 (20.49 GB)
telemt_user_octets_to_client{user="hello"} 231111076430 (215.24 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 26
```