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

# Server Metrics 2026-03-20 03:11:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 35608.3 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 657568
telemt_connections_bad_total 42957
telemt_connections_current 822
telemt_connections_me_current 822
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14713
telemt_upstream_connect_attempt_total 7298
telemt_upstream_connect_success_total 7207
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 7298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4351
telemt_me_reconnect_success_total 4311
telemt_me_reader_eof_total 4556
telemt_me_idle_close_by_peer_total 4555
telemt_me_route_drop_no_conn_total 185142
telemt_me_route_drop_channel_closed_total 59
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521963
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2460
telemt_desync_full_logged_total 895
telemt_desync_suppressed_total 1565
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 879
telemt_desync_frames_bucket_total{bucket="gt_10"} 1072
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4348
telemt_me_writer_restored_same_endpoint_total 4298
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 523395
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 30914407796 (28.79 GB)
telemt_user_octets_to_client{user="hello"} 179483961809 (167.16 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 52063.7 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3174215
telemt_connections_bad_total 173072
telemt_connections_current 2014
telemt_connections_me_current 2014
telemt_handshake_timeouts_total 69612
telemt_upstream_connect_attempt_total 10168
telemt_upstream_connect_success_total 9991
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 10168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10430
telemt_me_reconnect_success_total 6182
telemt_me_reader_eof_total 6614
telemt_me_idle_close_by_peer_total 6614
telemt_me_route_drop_no_conn_total 1538664
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2690610
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11500
telemt_desync_full_logged_total 3801
telemt_desync_suppressed_total 7699
telemt_desync_frames_bucket_total{bucket="1_2"} 2208
telemt_desync_frames_bucket_total{bucket="3_10"} 4492
telemt_desync_frames_bucket_total{bucket="gt_10"} 4800
telemt_pool_swap_total 45
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6386
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6127
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 2690345
telemt_user_connections_current{user="hello"} 2014
telemt_user_octets_from_client{user="hello"} 40928655922 (38.12 GB)
telemt_user_octets_to_client{user="hello"} 1000767279030 (932.04 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 52041.9 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3056860
telemt_connections_bad_total 480439
telemt_connections_current 1657
telemt_connections_me_current 1657
telemt_handshake_timeouts_total 48876
telemt_upstream_connect_attempt_total 8491
telemt_upstream_connect_success_total 8430
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6786
telemt_me_reconnect_success_total 5850
telemt_me_reader_eof_total 6147
telemt_me_idle_close_by_peer_total 6146
telemt_me_route_drop_no_conn_total 1949432
telemt_me_route_drop_channel_closed_total 174
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2116342
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7946
telemt_desync_full_logged_total 2431
telemt_desync_suppressed_total 5515
telemt_desync_frames_bucket_total{bucket="1_2"} 1948
telemt_desync_frames_bucket_total{bucket="3_10"} 3011
telemt_desync_frames_bucket_total{bucket="gt_10"} 2987
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 71
telemt_me_writer_removed_unexpected_total 5908
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5849
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2111918
telemt_user_connections_current{user="hello"} 1657
telemt_user_octets_from_client{user="hello"} 32180053668 (29.97 GB)
telemt_user_octets_to_client{user="hello"} 819697772368 (763.40 GB)
telemt_user_unique_ips_current{user="hello"} 625
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 52029.6 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2734061
telemt_connections_bad_total 205613
telemt_connections_current 1427
telemt_connections_me_current 1427
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 32435
telemt_upstream_connect_attempt_total 56369
telemt_upstream_connect_success_total 52058
telemt_upstream_connect_fail_total 4311
telemt_upstream_connect_attempts_per_request{bucket="1"} 56369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4311
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9091
telemt_me_reconnect_success_total 6229
telemt_me_reader_eof_total 6498
telemt_me_idle_close_by_peer_total 6497
telemt_me_route_drop_no_conn_total 1887856
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2217427
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8593
telemt_desync_full_logged_total 2734
telemt_desync_suppressed_total 5859
telemt_desync_frames_bucket_total{bucket="1_2"} 2123
telemt_desync_frames_bucket_total{bucket="3_10"} 3133
telemt_desync_frames_bucket_total{bucket="gt_10"} 3337
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6871
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6225
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 642
telemt_user_connections_total{user="hello"} 2259512
telemt_user_connections_current{user="hello"} 1427
telemt_user_octets_from_client{user="hello"} 36474263217 (33.97 GB)
telemt_user_octets_to_client{user="hello"} 649875516249 (605.24 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 105752.9 (29h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6392169
telemt_connections_bad_total 1064643
telemt_connections_current 1628
telemt_connections_me_current 1628
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 115419
telemt_upstream_connect_attempt_total 128486
telemt_upstream_connect_success_total 95196
telemt_upstream_connect_fail_total 33290
telemt_upstream_connect_attempts_per_request{bucket="1"} 128486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33290
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79282
telemt_me_reconnect_success_total 13609
telemt_me_reader_eof_total 14650
telemt_me_idle_close_by_peer_total 14636
telemt_me_route_drop_no_conn_total 2828419
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4538798
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
telemt_desync_total 19823
telemt_desync_full_logged_total 6292
telemt_desync_suppressed_total 13531
telemt_desync_frames_bucket_total{bucket="1_2"} 3498
telemt_desync_frames_bucket_total{bucket="3_10"} 8195
telemt_desync_frames_bucket_total{bucket="gt_10"} 8130
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 13923
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13584
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 4613875
telemt_user_connections_current{user="hello"} 1628
telemt_user_octets_from_client{user="hello"} 73418107516 (68.38 GB)
telemt_user_octets_to_client{user="hello"} 1791802125364 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 51992.8 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979791
telemt_connections_bad_total 83205
telemt_connections_current 751
telemt_connections_me_current 751
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13371
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
telemt_me_route_drop_no_conn_total 472635
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
telemt_desync_total 1418
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 596
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
telemt_user_connections_total{user="hello"} 830088
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 7805749675 (7.27 GB)
telemt_user_octets_to_client{user="hello"} 146582737274 (136.52 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 51994.2 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2116769
telemt_connections_bad_total 124509
telemt_connections_current 1511
telemt_connections_me_current 1511
telemt_handshake_timeouts_total 39446
telemt_upstream_connect_attempt_total 9375
telemt_upstream_connect_success_total 9312
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 9375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6767
telemt_me_reconnect_success_total 6722
telemt_me_reader_eof_total 7099
telemt_me_idle_close_by_peer_total 7099
telemt_me_route_drop_no_conn_total 766458
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1804893
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9425
telemt_desync_full_logged_total 3039
telemt_desync_suppressed_total 6386
telemt_desync_frames_bucket_total{bucket="1_2"} 1804
telemt_desync_frames_bucket_total{bucket="3_10"} 3298
telemt_desync_frames_bucket_total{bucket="gt_10"} 4323
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6818
telemt_me_writer_restored_same_endpoint_total 6705
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 1803994
telemt_user_connections_current{user="hello"} 1511
telemt_user_octets_from_client{user="hello"} 30593986124 (28.49 GB)
telemt_user_octets_to_client{user="hello"} 923945271536 (860.49 GB)
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 136
```