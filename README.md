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

# Server Metrics 2026-03-20 02:30:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 33160.7 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616718
telemt_connections_bad_total 39119
telemt_connections_current 849
telemt_connections_me_current 849
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10457
telemt_upstream_connect_attempt_total 6848
telemt_upstream_connect_success_total 6761
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 6848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4034
telemt_me_reconnect_success_total 3996
telemt_me_reader_eof_total 4220
telemt_me_idle_close_by_peer_total 4219
telemt_me_route_drop_no_conn_total 175630
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492275
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2316
telemt_desync_full_logged_total 837
telemt_desync_suppressed_total 1479
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 1028
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4029
telemt_me_writer_restored_same_endpoint_total 3983
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 493708
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 30337172112 (28.25 GB)
telemt_user_octets_to_client{user="hello"} 173024945465 (161.14 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 49616.1 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3077405
telemt_connections_bad_total 141590
telemt_connections_current 1683
telemt_connections_me_current 1683
telemt_handshake_timeouts_total 67760
telemt_upstream_connect_attempt_total 9799
telemt_upstream_connect_success_total 9630
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 9799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10155
telemt_me_reconnect_success_total 5909
telemt_me_reader_eof_total 6320
telemt_me_idle_close_by_peer_total 6320
telemt_me_route_drop_no_conn_total 1519659
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2629571
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11280
telemt_desync_full_logged_total 3724
telemt_desync_suppressed_total 7556
telemt_desync_frames_bucket_total{bucket="1_2"} 2153
telemt_desync_frames_bucket_total{bucket="3_10"} 4411
telemt_desync_frames_bucket_total{bucket="gt_10"} 4716
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6109
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5854
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 2629342
telemt_user_connections_current{user="hello"} 1683
telemt_user_octets_from_client{user="hello"} 40057221638 (37.31 GB)
telemt_user_octets_to_client{user="hello"} 976051184514 (909.02 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 49594.3 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3004721
telemt_connections_bad_total 477273
telemt_connections_current 1232
telemt_connections_me_current 1232
telemt_handshake_timeouts_total 45895
telemt_upstream_connect_attempt_total 8084
telemt_upstream_connect_success_total 8026
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 8084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6468
telemt_me_reconnect_success_total 5534
telemt_me_reader_eof_total 5811
telemt_me_idle_close_by_peer_total 5810
telemt_me_route_drop_no_conn_total 1934334
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2074145
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7801
telemt_desync_full_logged_total 2378
telemt_desync_suppressed_total 5423
telemt_desync_frames_bucket_total{bucket="1_2"} 1911
telemt_desync_frames_bucket_total{bucket="3_10"} 2962
telemt_desync_frames_bucket_total{bucket="gt_10"} 2928
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5588
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5533
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 2069769
telemt_user_connections_current{user="hello"} 1232
telemt_user_octets_from_client{user="hello"} 30423595872 (28.33 GB)
telemt_user_octets_to_client{user="hello"} 796710111256 (741.99 GB)
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 49581.9 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2659107
telemt_connections_bad_total 176250
telemt_connections_current 1186
telemt_connections_me_current 1186
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31762
telemt_upstream_connect_attempt_total 55931
telemt_upstream_connect_success_total 51635
telemt_upstream_connect_fail_total 4296
telemt_upstream_connect_attempts_per_request{bucket="1"} 55931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 531
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4296
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8754
telemt_me_reconnect_success_total 5904
telemt_me_reader_eof_total 6147
telemt_me_idle_close_by_peer_total 6146
telemt_me_route_drop_no_conn_total 1875857
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2177626
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8413
telemt_desync_full_logged_total 2666
telemt_desync_suppressed_total 5747
telemt_desync_frames_bucket_total{bucket="1_2"} 2068
telemt_desync_frames_bucket_total{bucket="3_10"} 3061
telemt_desync_frames_bucket_total{bucket="gt_10"} 3284
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6540
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5900
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 2219698
telemt_user_connections_current{user="hello"} 1186
telemt_user_octets_from_client{user="hello"} 36038947273 (33.56 GB)
telemt_user_octets_to_client{user="hello"} 627436985069 (584.35 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 103305.3 (28h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6330700
telemt_connections_bad_total 1050309
telemt_connections_current 1330
telemt_connections_me_current 1330
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 114512
telemt_upstream_connect_attempt_total 128036
telemt_upstream_connect_success_total 94749
telemt_upstream_connect_fail_total 33287
telemt_upstream_connect_attempts_per_request{bucket="1"} 128036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1435
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33287
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78964
telemt_me_reconnect_success_total 13293
telemt_me_reader_eof_total 14312
telemt_me_idle_close_by_peer_total 14298
telemt_me_route_drop_no_conn_total 2812145
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4494395
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
telemt_desync_total 19660
telemt_desync_full_logged_total 6232
telemt_desync_suppressed_total 13428
telemt_desync_frames_bucket_total{bucket="1_2"} 3462
telemt_desync_frames_bucket_total{bucket="3_10"} 8101
telemt_desync_frames_bucket_total{bucket="gt_10"} 8097
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 13602
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13268
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4569615
telemt_user_connections_current{user="hello"} 1330
telemt_user_octets_from_client{user="hello"} 72938274420 (67.93 GB)
telemt_user_octets_to_client{user="hello"} 1756864022920 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 49545.2 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809582
telemt_connections_bad_total 79859
telemt_connections_current 528
telemt_connections_me_current 528
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13126
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 472252
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 665664
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 7513068811 (7.00 GB)
telemt_user_octets_to_client{user="hello"} 146568827102 (136.50 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 49546.6 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2072915
telemt_connections_bad_total 122390
telemt_connections_current 1364
telemt_connections_me_current 1364
telemt_handshake_timeouts_total 38214
telemt_upstream_connect_attempt_total 8893
telemt_upstream_connect_success_total 8832
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6402
telemt_me_reconnect_success_total 6357
telemt_me_reader_eof_total 6710
telemt_me_idle_close_by_peer_total 6710
telemt_me_route_drop_no_conn_total 754403
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1772343
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9326
telemt_desync_full_logged_total 3003
telemt_desync_suppressed_total 6323
telemt_desync_frames_bucket_total{bucket="1_2"} 1770
telemt_desync_frames_bucket_total{bucket="3_10"} 3265
telemt_desync_frames_bucket_total{bucket="gt_10"} 4291
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6450
telemt_me_writer_restored_same_endpoint_total 6340
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 1771451
telemt_user_connections_current{user="hello"} 1364
telemt_user_octets_from_client{user="hello"} 30223171216 (28.15 GB)
telemt_user_octets_to_client{user="hello"} 903731897584 (841.67 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 123
```