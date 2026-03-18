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

# Server Metrics 2026-03-18 02:43:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 115091.1 (31h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1326521
telemt_connections_bad_total 10363
telemt_handshake_timeouts_total 33186
telemt_upstream_connect_attempt_total 25520
telemt_upstream_connect_success_total 25013
telemt_upstream_connect_fail_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 25520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 507
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34142
telemt_me_reconnect_success_total 17002
telemt_me_reader_eof_total 18454
telemt_me_idle_close_by_peer_total 18453
telemt_me_route_drop_no_conn_total 572279
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1221010
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7779
telemt_desync_full_logged_total 2306
telemt_desync_suppressed_total 5473
telemt_desync_frames_bucket_total{bucket="1_2"} 2072
telemt_desync_frames_bucket_total{bucket="3_10"} 2967
telemt_desync_frames_bucket_total{bucket="gt_10"} 2740
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17790
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16980
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 788
telemt_user_connections_total{user="hello"} 1215222
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 24677540167 (22.98 GB)
telemt_user_octets_to_client{user="hello"} 430040064283 (400.51 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 115342.5 (32h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1398875
telemt_connections_bad_total 64254
telemt_handshake_timeouts_total 47284
telemt_upstream_connect_attempt_total 468522
telemt_upstream_connect_success_total 466937
telemt_upstream_connect_fail_total 1585
telemt_upstream_connect_attempts_per_request{bucket="1"} 468522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1585
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123690
telemt_me_reconnect_success_total 18249
telemt_me_reader_eof_total 20423
telemt_me_idle_close_by_peer_total 20410
telemt_me_route_drop_no_conn_total 360692
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 774448
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3625
telemt_desync_full_logged_total 1242
telemt_desync_suppressed_total 2383
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 1511
telemt_desync_frames_bucket_total{bucket="gt_10"} 1399
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 19816
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 18231
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1567
telemt_user_connections_total{user="hello"} 1216798
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 16408803609 (15.28 GB)
telemt_user_octets_to_client{user="hello"} 427937465270 (398.55 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 115118.5 (31h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 848001
telemt_connections_bad_total 59287
telemt_handshake_timeouts_total 24698
telemt_upstream_connect_attempt_total 26854
telemt_upstream_connect_success_total 26699
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 26854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41627
telemt_me_reconnect_success_total 20933
telemt_me_reader_eof_total 22774
telemt_me_idle_close_by_peer_total 22767
telemt_me_route_drop_no_conn_total 333766
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 713184
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2243
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1515
telemt_desync_frames_bucket_total{bucket="1_2"} 641
telemt_desync_frames_bucket_total{bucket="3_10"} 872
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 21861
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20921
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 928
telemt_user_connections_total{user="hello"} 711302
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 44105820764 (41.08 GB)
telemt_user_octets_to_client{user="hello"} 317916122056 (296.08 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 115177.9 (31h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1325324
telemt_connections_bad_total 60312
telemt_handshake_timeouts_total 22156
telemt_upstream_connect_attempt_total 89592
telemt_upstream_connect_success_total 87178
telemt_upstream_connect_fail_total 2414
telemt_upstream_connect_attempts_per_request{bucket="1"} 89592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2414
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37087
telemt_me_reconnect_success_total 16690
telemt_me_reader_eof_total 18379
telemt_me_idle_close_by_peer_total 18377
telemt_me_route_drop_no_conn_total 543955
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1076621
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3986
telemt_desync_full_logged_total 1320
telemt_desync_suppressed_total 2666
telemt_desync_frames_bucket_total{bucket="1_2"} 974
telemt_desync_frames_bucket_total{bucket="3_10"} 1673
telemt_desync_frames_bucket_total{bucket="gt_10"} 1339
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17642
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16679
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 952
telemt_user_connections_total{user="hello"} 1139995
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 17849182114 (16.62 GB)
telemt_user_octets_to_client{user="hello"} 540684750890 (503.55 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 115149.7 (31h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 885382
telemt_connections_bad_total 101027
telemt_handshake_timeouts_total 6948
telemt_upstream_connect_attempt_total 46416
telemt_upstream_connect_success_total 45784
telemt_upstream_connect_fail_total 632
telemt_upstream_connect_attempts_per_request{bucket="1"} 46416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 632
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58541
telemt_me_reconnect_success_total 23578
telemt_me_reader_eof_total 25556
telemt_me_idle_close_by_peer_total 25553
telemt_me_route_drop_no_conn_total 282071
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715561
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3295
telemt_desync_full_logged_total 987
telemt_desync_suppressed_total 2308
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1315
telemt_desync_frames_bucket_total{bucket="gt_10"} 951
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25045
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23570
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1467
telemt_user_connections_total{user="hello"} 732118
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 13986236360 (13.03 GB)
telemt_user_octets_to_client{user="hello"} 360345980836 (335.60 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 115310.7 (32h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1132972
telemt_connections_bad_total 124042
telemt_handshake_timeouts_total 9911
telemt_upstream_connect_attempt_total 22951
telemt_upstream_connect_success_total 22820
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 22951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28350
telemt_me_reconnect_success_total 17061
telemt_me_reader_eof_total 18498
telemt_me_idle_close_by_peer_total 18496
telemt_me_route_drop_no_conn_total 782425
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1108224
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
telemt_pool_swap_total 103
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17683
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17047
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 927888
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 14957160868 (13.93 GB)
telemt_user_octets_to_client{user="hello"} 405855746456 (377.98 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 63077.9 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434601
telemt_connections_bad_total 44769
telemt_handshake_timeouts_total 11579
telemt_upstream_connect_attempt_total 23170
telemt_upstream_connect_success_total 22941
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 23170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31248
telemt_me_reconnect_success_total 19640
telemt_me_reader_eof_total 20762
telemt_me_idle_close_by_peer_total 20762
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 107004
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314612
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1376
telemt_desync_full_logged_total 441
telemt_desync_suppressed_total 935
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20220
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19601
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 314548
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 22675505969 (21.12 GB)
telemt_user_octets_to_client{user="hello"} 263954214414 (245.83 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 41
```