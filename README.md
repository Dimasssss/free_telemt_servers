# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 19:23:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 7571.6 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239749
telemt_connections_bad_total 9871
telemt_connections_current 1254
telemt_connections_me_current 1254
telemt_handshake_timeouts_total 2425
telemt_upstream_connect_attempt_total 1152
telemt_upstream_connect_success_total 1138
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 727
telemt_me_reconnect_success_total 722
telemt_me_reader_eof_total 748
telemt_me_idle_close_by_peer_total 748
telemt_me_route_drop_no_conn_total 72221
telemt_me_route_drop_channel_closed_total 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185529
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 883
telemt_desync_full_logged_total 291
telemt_desync_suppressed_total 592
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 437
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 742
telemt_me_writer_restored_same_endpoint_total 709
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 185786
telemt_user_connections_current{user="hello"} 1254
telemt_user_octets_from_client{user="hello"} 5264886764 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 65406969772 (60.91 GB)
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 24026.7 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2295865
telemt_connections_bad_total 103553
telemt_connections_current 3444
telemt_connections_me_current 3444
telemt_handshake_timeouts_total 43746
telemt_upstream_connect_attempt_total 5225
telemt_upstream_connect_success_total 5156
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 5225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6928
telemt_me_reconnect_success_total 2702
telemt_me_reader_eof_total 2916
telemt_me_idle_close_by_peer_total 2916
telemt_me_route_drop_no_conn_total 1264151
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1931878
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7958
telemt_desync_full_logged_total 2568
telemt_desync_suppressed_total 5390
telemt_desync_frames_bucket_total{bucket="1_2"} 1476
telemt_desync_frames_bucket_total{bucket="3_10"} 3133
telemt_desync_frames_bucket_total{bucket="gt_10"} 3349
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2853
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2647
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 1931884
telemt_user_connections_current{user="hello"} 3444
telemt_user_octets_from_client{user="hello"} 28297339130 (26.35 GB)
telemt_user_octets_to_client{user="hello"} 648244609934 (603.72 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1215
telemt_user_unique_ips_recent_window{user="hello"} 443
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 24005.3 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2081386
telemt_connections_bad_total 247027
telemt_connections_current 2629
telemt_connections_me_current 2629
telemt_handshake_timeouts_total 24255
telemt_upstream_connect_attempt_total 3730
telemt_upstream_connect_success_total 3705
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3398
telemt_me_reconnect_success_total 2479
telemt_me_reader_eof_total 2546
telemt_me_idle_close_by_peer_total 2545
telemt_me_route_drop_no_conn_total 1741771
telemt_me_route_drop_channel_closed_total 152
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1583811
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5546
telemt_desync_full_logged_total 1657
telemt_desync_suppressed_total 3889
telemt_desync_frames_bucket_total{bucket="1_2"} 1404
telemt_desync_frames_bucket_total{bucket="3_10"} 2094
telemt_desync_frames_bucket_total{bucket="gt_10"} 2048
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 54
telemt_me_writer_removed_unexpected_total 2480
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2478
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1580166
telemt_user_connections_current{user="hello"} 2629
telemt_user_octets_from_client{user="hello"} 21636690100 (20.15 GB)
telemt_user_octets_to_client{user="hello"} 531810412744 (495.29 GB)
telemt_user_unique_ips_current{user="hello"} 880
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 23992.8 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1954508
telemt_connections_bad_total 63821
telemt_connections_current 2474
telemt_connections_me_current 2474
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 25031
telemt_upstream_connect_attempt_total 25797
telemt_upstream_connect_success_total 24591
telemt_upstream_connect_fail_total 1206
telemt_upstream_connect_attempts_per_request{bucket="1"} 25797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1206
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5329
telemt_me_reconnect_success_total 2940
telemt_me_reader_eof_total 3051
telemt_me_idle_close_by_peer_total 3050
telemt_me_route_drop_no_conn_total 1677081
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1687393
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6765
telemt_desync_full_logged_total 2099
telemt_desync_suppressed_total 4666
telemt_desync_frames_bucket_total{bucket="1_2"} 1707
telemt_desync_frames_bucket_total{bucket="3_10"} 2489
telemt_desync_frames_bucket_total{bucket="gt_10"} 2569
telemt_pool_swap_total 11
telemt_me_writer_close_signal_drop_total 201
telemt_me_writer_removed_unexpected_total 3357
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2936
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 1706717
telemt_user_connections_current{user="hello"} 2474
telemt_user_octets_from_client{user="hello"} 28691276373 (26.72 GB)
telemt_user_octets_to_client{user="hello"} 386309443033 (359.78 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 901
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 77716.1 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5642867
telemt_connections_bad_total 1014900
telemt_connections_current 2948
telemt_connections_me_current 2948
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 103097
telemt_upstream_connect_attempt_total 65336
telemt_upstream_connect_success_total 62839
telemt_upstream_connect_fail_total 2497
telemt_upstream_connect_attempts_per_request{bucket="1"} 65336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2497
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75171
telemt_me_reconnect_success_total 9760
telemt_me_reader_eof_total 10294
telemt_me_idle_close_by_peer_total 10291
telemt_me_route_drop_no_conn_total 2581262
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3942083
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17384
telemt_desync_full_logged_total 5339
telemt_desync_suppressed_total 12045
telemt_desync_frames_bucket_total{bucket="1_2"} 2906
telemt_desync_frames_bucket_total{bucket="3_10"} 7207
telemt_desync_frames_bucket_total{bucket="gt_10"} 7271
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 10011
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9736
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 3990193
telemt_user_connections_current{user="hello"} 2948
telemt_user_octets_from_client{user="hello"} 62217305091 (57.94 GB)
telemt_user_octets_to_client{user="hello"} 1481668873460 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1065
telemt_user_unique_ips_recent_window{user="hello"} 398
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 23957.2 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539262
telemt_connections_bad_total 40149
telemt_connections_current 618
telemt_connections_me_current 618
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10759
telemt_upstream_connect_attempt_total 7550
telemt_upstream_connect_success_total 7353
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3194
telemt_me_reconnect_success_total 3136
telemt_me_reader_eof_total 3229
telemt_me_idle_close_by_peer_total 3228
telemt_me_route_drop_no_conn_total 371706
telemt_me_route_drop_channel_closed_total 132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427391
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1121
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 767
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 134
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3160
telemt_me_writer_restored_same_endpoint_total 3127
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 446033
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 5117322324 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 93505125682 (87.08 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 23957.6 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1538029
telemt_connections_bad_total 91845
telemt_connections_current 2844
telemt_connections_me_current 2844
telemt_handshake_timeouts_total 25578
telemt_upstream_connect_attempt_total 3948
telemt_upstream_connect_success_total 3918
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2714
telemt_me_reconnect_success_total 2685
telemt_me_reader_eof_total 2817
telemt_me_idle_close_by_peer_total 2817
telemt_me_route_drop_no_conn_total 588323
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1336294
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7020
telemt_desync_full_logged_total 2167
telemt_desync_suppressed_total 4853
telemt_desync_frames_bucket_total{bucket="1_2"} 1330
telemt_desync_frames_bucket_total{bucket="3_10"} 2440
telemt_desync_frames_bucket_total{bucket="gt_10"} 3250
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2740
telemt_me_writer_restored_same_endpoint_total 2668
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1335543
telemt_user_connections_current{user="hello"} 2844
telemt_user_octets_from_client{user="hello"} 21323140364 (19.86 GB)
telemt_user_octets_to_client{user="hello"} 608914422676 (567.10 GB)
telemt_user_unique_ips_current{user="hello"} 932
telemt_user_unique_ips_recent_window{user="hello"} 321
```