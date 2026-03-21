# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
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

## rdp-onedash.ru (2 сервера)
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

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-21 16:03:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 70081.1 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2501101
telemt_connections_bad_total 149213
telemt_connections_current 1426
telemt_connections_me_current 1426
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 78963
telemt_upstream_connect_attempt_total 29694
telemt_upstream_connect_success_total 29563
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 29651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1717
telemt_me_reconnect_success_total 676
telemt_me_reader_eof_total 649
telemt_me_idle_close_by_peer_total 649
telemt_me_route_drop_no_conn_total 2131745
telemt_me_route_drop_channel_closed_total 662
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1991356
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 488
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 545
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 7928
telemt_desync_full_logged_total 2733
telemt_desync_suppressed_total 5195
telemt_desync_frames_bucket_total{bucket="1_2"} 1738
telemt_desync_frames_bucket_total{bucket="3_10"} 3006
telemt_desync_frames_bucket_total{bucket="gt_10"} 3184
telemt_pool_swap_total 75
telemt_pool_force_close_total 2271
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 511
telemt_me_draining_writers_reap_progress_total 23838
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2046
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22203
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2152
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21567
telemt_me_writer_teardown_success_total{mode="normal"} 24249
telemt_me_writer_teardown_noop_total 23844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 223.409200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 511
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 578
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 1992758
telemt_user_connections_current{user="hello"} 1426
telemt_user_octets_from_client{user="hello"} 28121827329 (26.19 GB)
telemt_user_octets_to_client{user="hello"} 493762801550 (459.85 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1205.8 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41925
telemt_connections_bad_total 2091
telemt_connections_current 958
telemt_connections_me_current 958
telemt_handshake_timeouts_total 918
telemt_upstream_connect_attempt_total 551
telemt_upstream_connect_success_total 551
telemt_upstream_connect_attempts_per_request{bucket="1"} 551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 20937
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35945
telemt_me_endpoint_quarantine_total 14
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 141
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 444
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 424
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 417
telemt_me_writer_teardown_success_total{mode="normal"} 445
telemt_me_writer_teardown_noop_total 444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 889
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.031241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 889
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 35522
telemt_user_connections_current{user="hello"} 958
telemt_user_octets_from_client{user="hello"} 277153748 (264.31 MB)
telemt_user_octets_to_client{user="hello"} 9454363504 (8.81 GB)
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 70078.2 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5089587
telemt_connections_bad_total 446682
telemt_connections_current 5728
telemt_connections_me_current 5728
telemt_handshake_timeouts_total 176019
telemt_upstream_connect_attempt_total 25856
telemt_upstream_connect_success_total 25801
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 25807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1165
telemt_me_reconnect_success_total 590
telemt_me_reader_eof_total 594
telemt_me_idle_close_by_peer_total 594
telemt_me_route_drop_no_conn_total 2995925
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4172313
telemt_me_endpoint_quarantine_total 439
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 528
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 17149
telemt_desync_full_logged_total 5764
telemt_desync_suppressed_total 11385
telemt_desync_frames_bucket_total{bucket="1_2"} 3625
telemt_desync_frames_bucket_total{bucket="3_10"} 6799
telemt_desync_frames_bucket_total{bucket="gt_10"} 6725
telemt_pool_swap_total 74
telemt_pool_force_close_total 2431
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 23471
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2057
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21731
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2232
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21040
telemt_me_writer_teardown_success_total{mode="normal"} 23788
telemt_me_writer_teardown_noop_total 23505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47293
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 90.743982
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47293
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 531
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4167372
telemt_user_connections_current{user="hello"} 5728
telemt_user_octets_from_client{user="hello"} 66387238896 (61.83 GB)
telemt_user_octets_to_client{user="hello"} 1348808403148 (1.23 TB)
telemt_user_unique_ips_current{user="hello"} 2192
telemt_user_unique_ips_recent_window{user="hello"} 809
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 70080.7 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4097307
telemt_connections_bad_total 431219
telemt_connections_current 3971
telemt_connections_me_current 3971
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 143374
telemt_upstream_connect_attempt_total 30219
telemt_upstream_connect_success_total 29932
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 30072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 495
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1390
telemt_me_reconnect_success_total 610
telemt_me_reader_eof_total 573
telemt_me_idle_close_by_peer_total 573
telemt_me_route_drop_no_conn_total 1307903
telemt_me_route_drop_channel_closed_total 107
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3016883
telemt_me_endpoint_quarantine_total 447
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 534
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 14318
telemt_desync_full_logged_total 4733
telemt_desync_suppressed_total 9585
telemt_desync_frames_bucket_total{bucket="1_2"} 3585
telemt_desync_frames_bucket_total{bucket="3_10"} 5536
telemt_desync_frames_bucket_total{bucket="gt_10"} 5197
telemt_pool_swap_total 76
telemt_pool_force_close_total 2219
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 22611
telemt_me_writer_removed_unexpected_total 555
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1944
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21213
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 158
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20392
telemt_me_writer_teardown_success_total{mode="normal"} 23157
telemt_me_writer_teardown_noop_total 22613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45770
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.109514
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45770
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 3016393
telemt_user_connections_current{user="hello"} 3971
telemt_user_octets_from_client{user="hello"} 66736430777 (62.15 GB)
telemt_user_octets_to_client{user="hello"} 1394314023067 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1591
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 70043.9 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4036308
telemt_connections_bad_total 412157
telemt_connections_current 3775
telemt_connections_me_current 3775
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 122149
telemt_upstream_connect_attempt_total 35494
telemt_upstream_connect_success_total 35255
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 864
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1458
telemt_me_reconnect_success_total 665
telemt_me_reader_eof_total 607
telemt_me_idle_close_by_peer_total 607
telemt_me_route_drop_no_conn_total 1398009
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2999574
telemt_me_endpoint_quarantine_total 494
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 525
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 13831
telemt_desync_full_logged_total 4578
telemt_desync_suppressed_total 9253
telemt_desync_frames_bucket_total{bucket="1_2"} 3451
telemt_desync_frames_bucket_total{bucket="3_10"} 5210
telemt_desync_frames_bucket_total{bucket="gt_10"} 5170
telemt_pool_swap_total 74
telemt_pool_force_close_total 2131
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 246
telemt_me_draining_writers_reap_progress_total 24034
telemt_me_writer_removed_unexpected_total 577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2034
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22615
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1947
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21903
telemt_me_writer_teardown_success_total{mode="normal"} 24649
telemt_me_writer_teardown_noop_total 24040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48689
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.813330
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48689
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 246
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 3003199
telemt_user_connections_current{user="hello"} 3775
telemt_user_octets_from_client{user="hello"} 69254639141 (64.50 GB)
telemt_user_octets_to_client{user="hello"} 1388375094844 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1532
telemt_user_unique_ips_recent_window{user="hello"} 600
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 70083.1 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13884860
telemt_connections_bad_total 897998
telemt_connections_current 5881
telemt_connections_me_current 5881
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 414697
telemt_upstream_connect_attempt_total 116632
telemt_upstream_connect_success_total 106711
telemt_upstream_connect_fail_total 8855
telemt_upstream_connect_attempts_per_request{bucket="1"} 115566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8855
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 3894
telemt_me_reconnect_success_total 1420
telemt_me_reader_eof_total 991
telemt_me_idle_close_by_peer_total 990
telemt_me_route_drop_no_conn_total 27398208
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11438305
telemt_me_endpoint_quarantine_total 536
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 548
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 20137
telemt_desync_full_logged_total 6298
telemt_desync_suppressed_total 13839
telemt_desync_frames_bucket_total{bucket="1_2"} 4398
telemt_desync_frames_bucket_total{bucket="3_10"} 8863
telemt_desync_frames_bucket_total{bucket="gt_10"} 6876
telemt_pool_swap_total 71
telemt_pool_force_close_total 2325
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 505
telemt_me_draining_writers_reap_progress_total 22347
telemt_me_writer_removed_unexpected_total 1352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2921
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20555
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1953
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 372
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20022
telemt_me_writer_teardown_success_total{mode="normal"} 23476
telemt_me_writer_teardown_noop_total 22359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 174.303820
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 505
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 994
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 11512982
telemt_user_connections_current{user="hello"} 5881
telemt_user_octets_from_client{user="hello"} 80349159485 (74.83 GB)
telemt_user_octets_to_client{user="hello"} 823629067373 (767.06 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2110
telemt_user_unique_ips_recent_window{user="hello"} 1034
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 70050.7 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4022175
telemt_connections_bad_total 436971
telemt_connections_current 4273
telemt_connections_me_current 4273
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 86069
telemt_upstream_connect_attempt_total 29338
telemt_upstream_connect_success_total 29018
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 29291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_reconnect_attempts_total 2777
telemt_me_reconnect_success_total 1037
telemt_me_reader_eof_total 1040
telemt_me_idle_close_by_peer_total 1040
telemt_me_route_drop_no_conn_total 1715069
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3114696
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 522
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 15047
telemt_desync_full_logged_total 5213
telemt_desync_suppressed_total 9834
telemt_desync_frames_bucket_total{bucket="1_2"} 2955
telemt_desync_frames_bucket_total{bucket="3_10"} 5976
telemt_desync_frames_bucket_total{bucket="gt_10"} 6116
telemt_pool_swap_total 69
telemt_pool_force_close_total 2034
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 206
telemt_me_draining_writers_reap_progress_total 24637
telemt_me_writer_removed_unexpected_total 1007
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2467
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23213
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1748
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22603
telemt_me_writer_teardown_success_total{mode="normal"} 25680
telemt_me_writer_teardown_noop_total 24638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50318
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.322061
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50318
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 206
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 898
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 3098026
telemt_user_connections_current{user="hello"} 4273
telemt_user_octets_from_client{user="hello"} 81236152848 (75.66 GB)
telemt_user_octets_to_client{user="hello"} 1279048969882 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1718
telemt_user_unique_ips_recent_window{user="hello"} 574
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 6886.3 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1075532
telemt_connections_bad_total 39975
telemt_connections_current 3710
telemt_connections_me_current 3710
telemt_handshake_timeouts_total 501080
telemt_upstream_connect_attempt_total 2433
telemt_upstream_connect_success_total 2390
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 298
telemt_me_reconnect_success_total 96
telemt_me_reader_eof_total 86
telemt_me_idle_close_by_peer_total 86
telemt_me_route_drop_no_conn_total 426264
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490527
telemt_me_endpoint_quarantine_total 27
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 2497
telemt_desync_full_logged_total 807
telemt_desync_suppressed_total 1690
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 910
telemt_desync_frames_bucket_total{bucket="gt_10"} 1108
telemt_pool_swap_total 6
telemt_pool_force_close_total 200
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 17
telemt_me_draining_writers_reap_progress_total 2057
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1951
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1857
telemt_me_writer_teardown_success_total{mode="normal"} 2144
telemt_me_writer_teardown_noop_total 2057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4201
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.818776
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4201
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 17
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 489808
telemt_user_connections_current{user="hello"} 3710
telemt_user_octets_from_client{user="hello"} 12600430372 (11.74 GB)
telemt_user_octets_to_client{user="hello"} 182945438516 (170.38 GB)
telemt_user_unique_ips_current{user="hello"} 1503
telemt_user_unique_ips_recent_window{user="hello"} 564
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 68036.6 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1285179
telemt_connections_bad_total 143754
telemt_connections_current 859
telemt_connections_me_current 859
telemt_handshake_timeouts_total 459703
telemt_upstream_connect_attempt_total 31653
telemt_upstream_connect_success_total 31645
telemt_upstream_connect_attempts_per_request{bucket="1"} 31645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1358
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 566
telemt_me_idle_close_by_peer_total 566
telemt_me_route_drop_no_conn_total 281703
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605128
telemt_me_endpoint_quarantine_total 604
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 569
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 3640
telemt_desync_full_logged_total 1318
telemt_desync_suppressed_total 2322
telemt_desync_frames_bucket_total{bucket="1_2"} 674
telemt_desync_frames_bucket_total{bucket="3_10"} 1311
telemt_desync_frames_bucket_total{bucket="gt_10"} 1655
telemt_pool_swap_total 74
telemt_pool_force_close_total 1739
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 28370
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2150
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26772
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1710
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26631
telemt_me_writer_teardown_success_total{mode="normal"} 28922
telemt_me_writer_teardown_noop_total 28370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57292
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.575243
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57292
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 604727
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 12523865303 (11.66 GB)
telemt_user_octets_to_client{user="hello"} 233582224589 (217.54 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 70055.1 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4481239
telemt_connections_bad_total 414521
telemt_connections_current 4867
telemt_connections_me_current 4867
telemt_handshake_timeouts_total 146872
telemt_upstream_connect_attempt_total 27684
telemt_upstream_connect_success_total 27571
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 27649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1190
telemt_me_reconnect_success_total 619
telemt_me_reader_eof_total 586
telemt_me_idle_close_by_peer_total 586
telemt_me_route_drop_no_conn_total 1359978
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3544953
telemt_me_endpoint_quarantine_total 502
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 534
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 13868
telemt_desync_full_logged_total 4583
telemt_desync_suppressed_total 9285
telemt_desync_frames_bucket_total{bucket="1_2"} 3275
telemt_desync_frames_bucket_total{bucket="3_10"} 5170
telemt_desync_frames_bucket_total{bucket="gt_10"} 5423
telemt_pool_swap_total 77
telemt_pool_force_close_total 2032
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 230
telemt_me_draining_writers_reap_progress_total 24840
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1983
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23433
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1984
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22808
telemt_me_writer_teardown_success_total{mode="normal"} 25416
telemt_me_writer_teardown_noop_total 24840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50256
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.091431
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50256
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 230
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3536375
telemt_user_connections_current{user="hello"} 4867
telemt_user_octets_from_client{user="hello"} 71067414568 (66.19 GB)
telemt_user_octets_to_client{user="hello"} 1658126545644 (1.51 TB)
telemt_user_unique_ips_current{user="hello"} 1746
telemt_user_unique_ips_recent_window{user="hello"} 709
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 70052.1 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3973443
telemt_connections_bad_total 361522
telemt_connections_current 4084
telemt_connections_me_current 4084
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 122239
telemt_upstream_connect_attempt_total 44183
telemt_upstream_connect_success_total 43872
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 44128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_reconnect_attempts_total 3949
telemt_me_reconnect_success_total 888
telemt_me_reader_eof_total 766
telemt_me_idle_close_by_peer_total 766
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1440318
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3166992
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 529
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 12320
telemt_desync_full_logged_total 4180
telemt_desync_suppressed_total 8140
telemt_desync_frames_bucket_total{bucket="1_2"} 3074
telemt_desync_frames_bucket_total{bucket="3_10"} 4578
telemt_desync_frames_bucket_total{bucket="gt_10"} 4668
telemt_pool_swap_total 75
telemt_pool_force_close_total 1971
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 218
telemt_me_draining_writers_reap_progress_total 24209
telemt_me_writer_removed_unexpected_total 779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2376
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22645
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1805
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 166
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22238
telemt_me_writer_teardown_success_total{mode="normal"} 25021
telemt_me_writer_teardown_noop_total 24210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49231
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.282591
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49231
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 218
telemt_me_refill_failed_total 174
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 3175224
telemt_user_connections_current{user="hello"} 4084
telemt_user_octets_from_client{user="hello"} 57601634073 (53.65 GB)
telemt_user_octets_to_client{user="hello"} 1353712297892 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1590
telemt_user_unique_ips_recent_window{user="hello"} 640
```