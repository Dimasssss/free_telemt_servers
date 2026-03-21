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

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
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
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
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

# Server Metrics 2026-03-21 20:44:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 86876.5 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3090783
telemt_connections_bad_total 180144
telemt_connections_current 1019
telemt_connections_me_current 1019
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 96782
telemt_upstream_connect_attempt_total 35508
telemt_upstream_connect_success_total 35359
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 35465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1932
telemt_me_reconnect_success_total 769
telemt_me_reader_eof_total 738
telemt_me_idle_close_by_peer_total 738
telemt_me_route_drop_no_conn_total 2626566
telemt_me_route_drop_channel_closed_total 845
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2501076
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 590
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 678
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
telemt_me_writers_active_current 44
telemt_desync_total 10002
telemt_desync_full_logged_total 3492
telemt_desync_suppressed_total 6510
telemt_desync_frames_bucket_total{bucket="1_2"} 2172
telemt_desync_frames_bucket_total{bucket="3_10"} 3742
telemt_desync_frames_bucket_total{bucket="gt_10"} 4088
telemt_pool_swap_total 94
telemt_pool_force_close_total 2844
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 29129
telemt_me_writer_removed_unexpected_total 720
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2450
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27139
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2704
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 140
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26285
telemt_me_writer_teardown_success_total{mode="normal"} 29589
telemt_me_writer_teardown_noop_total 29137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58726
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 300.124663
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58726
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 661
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2500673
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 37068650789 (34.52 GB)
telemt_user_octets_to_client{user="hello"} 637889931782 (594.08 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 12014.9 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474415
telemt_connections_bad_total 22568
telemt_connections_current 790
telemt_connections_me_current 790
telemt_handshake_timeouts_total 16760
telemt_upstream_connect_attempt_total 4760
telemt_upstream_connect_success_total 4663
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_reconnect_attempts_total 330
telemt_me_reconnect_success_total 149
telemt_me_reader_eof_total 127
telemt_me_idle_close_by_peer_total 127
telemt_me_route_drop_no_conn_total 278215
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386148
telemt_me_endpoint_quarantine_total 91
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 1655
telemt_desync_full_logged_total 949
telemt_desync_suppressed_total 706
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 632
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 13
telemt_pool_force_close_total 392
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 4143
telemt_me_writer_removed_unexpected_total 120
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 357
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3900
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 385
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3751
telemt_me_writer_teardown_success_total{mode="normal"} 4257
telemt_me_writer_teardown_noop_total 4143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8400
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.241811
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8400
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 101
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 385657
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 6405326120 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 116920821788 (108.89 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 86875.1 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6915952
telemt_connections_bad_total 536988
telemt_connections_current 3489
telemt_connections_me_current 3489
telemt_handshake_timeouts_total 215564
telemt_upstream_connect_attempt_total 31203
telemt_upstream_connect_success_total 31140
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 31147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 672
telemt_me_reader_eof_total 682
telemt_me_idle_close_by_peer_total 682
telemt_me_route_drop_no_conn_total 4365614
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5658370
telemt_me_endpoint_quarantine_total 537
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 646
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 23384
telemt_desync_full_logged_total 7777
telemt_desync_suppressed_total 15607
telemt_desync_frames_bucket_total{bucket="1_2"} 4887
telemt_desync_frames_bucket_total{bucket="3_10"} 9303
telemt_desync_frames_bucket_total{bucket="gt_10"} 9194
telemt_pool_swap_total 93
telemt_pool_force_close_total 3128
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 509
telemt_me_draining_writers_reap_progress_total 28394
telemt_me_writer_removed_unexpected_total 656
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2439
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26238
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25266
telemt_me_writer_teardown_success_total{mode="normal"} 28677
telemt_me_writer_teardown_noop_total 28431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57108
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 139.241155
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57108
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 509
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 603
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 5651568
telemt_user_connections_current{user="hello"} 3489
telemt_user_octets_from_client{user="hello"} 97207965952 (90.53 GB)
telemt_user_octets_to_client{user="hello"} 1779611514604 (1.62 TB)
telemt_user_unique_ips_current{user="hello"} 1403
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 86876.6 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5599722
telemt_connections_bad_total 540864
telemt_connections_current 3017
telemt_connections_me_current 3017
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 184163
telemt_upstream_connect_attempt_total 35281
telemt_upstream_connect_success_total 34963
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 35127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1672
telemt_me_reconnect_success_total 698
telemt_me_reader_eof_total 672
telemt_me_idle_close_by_peer_total 672
telemt_me_route_drop_no_conn_total 1936220
telemt_me_route_drop_channel_closed_total 221
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4189971
telemt_me_endpoint_quarantine_total 532
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 663
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
telemt_me_writers_active_current 44
telemt_desync_total 19965
telemt_desync_full_logged_total 6615
telemt_desync_suppressed_total 13350
telemt_desync_frames_bucket_total{bucket="1_2"} 4884
telemt_desync_frames_bucket_total{bucket="3_10"} 7723
telemt_desync_frames_bucket_total{bucket="gt_10"} 7358
telemt_pool_swap_total 95
telemt_pool_force_close_total 2882
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 323
telemt_me_draining_writers_reap_progress_total 27159
telemt_me_writer_removed_unexpected_total 651
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2357
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25382
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2687
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 195
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24277
telemt_me_writer_teardown_success_total{mode="normal"} 27739
telemt_me_writer_teardown_noop_total 27164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54903
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.950554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54903
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 323
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 598
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4182630
telemt_user_connections_current{user="hello"} 3017
telemt_user_octets_from_client{user="hello"} 125861483737 (117.22 GB)
telemt_user_octets_to_client{user="hello"} 1917757347987 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1229
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 86839.5 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5526251
telemt_connections_bad_total 498233
telemt_connections_current 2951
telemt_connections_me_current 2951
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 167926
telemt_upstream_connect_attempt_total 41723
telemt_upstream_connect_success_total 41455
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 41590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1731
telemt_me_reconnect_success_total 764
telemt_me_reader_eof_total 708
telemt_me_idle_close_by_peer_total 708
telemt_me_route_drop_no_conn_total 1991113
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4175155
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 647
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 19706
telemt_desync_full_logged_total 6437
telemt_desync_suppressed_total 13269
telemt_desync_frames_bucket_total{bucket="1_2"} 4912
telemt_desync_frames_bucket_total{bucket="3_10"} 7467
telemt_desync_frames_bucket_total{bucket="gt_10"} 7327
telemt_pool_swap_total 93
telemt_pool_force_close_total 2747
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 334
telemt_me_draining_writers_reap_progress_total 28592
telemt_me_writer_removed_unexpected_total 678
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2453
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26838
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2534
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25845
telemt_me_writer_teardown_success_total{mode="normal"} 29291
telemt_me_writer_teardown_noop_total 28602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.229641
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 334
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4177266
telemt_user_connections_current{user="hello"} 2951
telemt_user_octets_from_client{user="hello"} 122035340767 (113.65 GB)
telemt_user_octets_to_client{user="hello"} 1907998893035 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1213
telemt_user_unique_ips_recent_window{user="hello"} 388
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 86926.5 (24h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19122477
telemt_connections_bad_total 1238885
telemt_connections_current 578
telemt_connections_direct_current 572
telemt_connections_me_current 6
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 533552
telemt_upstream_connect_attempt_total 176269
telemt_upstream_connect_success_total 159088
telemt_upstream_connect_fail_total 15598
telemt_upstream_connect_attempts_per_request{bucket="1"} 174686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8836
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15598
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59559
telemt_me_reconnect_success_total 1821
telemt_me_reader_eof_total 1206
telemt_me_idle_close_by_peer_total 1205
telemt_me_route_drop_no_conn_total 39071198
telemt_me_route_drop_channel_closed_total 115
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15729608
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 640
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 104
telemt_me_single_endpoint_outage_reconnect_attempt_total 238
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 238
telemt_me_single_endpoint_shadow_rotate_total 675
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 8
telemt_desync_total 29418
telemt_desync_full_logged_total 8673
telemt_desync_suppressed_total 20745
telemt_desync_frames_bucket_total{bucket="1_2"} 6443
telemt_desync_frames_bucket_total{bucket="3_10"} 13031
telemt_desync_frames_bucket_total{bucket="gt_10"} 9944
telemt_pool_swap_total 89
telemt_pool_force_close_total 2975
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 26771
telemt_me_writer_removed_unexpected_total 1739
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23796
telemt_me_writer_teardown_success_total{mode="normal"} 28254
telemt_me_writer_teardown_noop_total 26797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55051
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.310671
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55051
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1273
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14223
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 15849917
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 151048641704 (140.68 GB)
telemt_user_octets_to_client{user="hello"} 971589207504 (904.86 GB)
telemt_user_msgs_from_client{user="hello"} 354018
telemt_user_msgs_to_client{user="hello"} 635091
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 371
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 86846.3 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5426284
telemt_connections_bad_total 523425
telemt_connections_current 3263
telemt_connections_me_current 3263
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 111743
telemt_upstream_connect_attempt_total 44837
telemt_upstream_connect_success_total 44350
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 44753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_reconnect_attempts_total 11069
telemt_me_reconnect_success_total 1269
telemt_me_reader_eof_total 1200
telemt_me_idle_close_by_peer_total 1200
telemt_me_route_drop_no_conn_total 2267690
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4212917
telemt_me_endpoint_quarantine_total 533
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 647
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 20858
telemt_desync_full_logged_total 7236
telemt_desync_suppressed_total 13622
telemt_desync_frames_bucket_total{bucket="1_2"} 3984
telemt_desync_frames_bucket_total{bucket="3_10"} 8133
telemt_desync_frames_bucket_total{bucket="gt_10"} 8741
telemt_pool_swap_total 88
telemt_pool_force_close_total 2605
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 322
telemt_me_draining_writers_reap_progress_total 29411
telemt_me_writer_removed_unexpected_total 1180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2999
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27605
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2243
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26806
telemt_me_writer_teardown_success_total{mode="normal"} 30604
telemt_me_writer_teardown_noop_total 29412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60016
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.363743
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60016
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 322
telemt_me_refill_failed_total 591
telemt_me_writer_restored_same_endpoint_total 1075
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4202629
telemt_user_connections_current{user="hello"} 3263
telemt_user_octets_from_client{user="hello"} 112131902261 (104.43 GB)
telemt_user_octets_to_client{user="hello"} 1703992018347 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1287
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 23682.1 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3147866
telemt_connections_bad_total 116472
telemt_connections_current 2631
telemt_connections_me_current 2631
telemt_handshake_timeouts_total 1354946
telemt_upstream_connect_attempt_total 7694
telemt_upstream_connect_success_total 7588
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 7688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_reconnect_attempts_total 2202
telemt_me_reconnect_success_total 262
telemt_me_reader_eof_total 203
telemt_me_idle_close_by_peer_total 203
telemt_me_route_drop_no_conn_total 913375
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1489822
telemt_me_endpoint_quarantine_total 121
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 178
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 8179
telemt_desync_full_logged_total 2720
telemt_desync_suppressed_total 5459
telemt_desync_frames_bucket_total{bucket="1_2"} 1463
telemt_desync_frames_bucket_total{bucket="3_10"} 3097
telemt_desync_frames_bucket_total{bucket="gt_10"} 3619
telemt_pool_swap_total 25
telemt_pool_force_close_total 815
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 6703
telemt_me_writer_removed_unexpected_total 221
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 639
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6292
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 107
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5888
telemt_me_writer_teardown_success_total{mode="normal"} 6931
telemt_me_writer_teardown_noop_total 6704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13635
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.139070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13635
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 213
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1485449
telemt_user_connections_current{user="hello"} 2631
telemt_user_octets_from_client{user="hello"} 44525612376 (41.47 GB)
telemt_user_octets_to_client{user="hello"} 615560953440 (573.29 GB)
telemt_user_unique_ips_current{user="hello"} 1104
telemt_user_unique_ips_recent_window{user="hello"} 373
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 4653.1 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52059
telemt_connections_bad_total 149
telemt_connections_current 526
telemt_connections_me_current 526
telemt_handshake_timeouts_total 793
telemt_upstream_connect_attempt_total 2069
telemt_upstream_connect_success_total 2062
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 55
telemt_me_reconnect_success_total 24
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 15246
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45569
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 44
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
telemt_me_writers_active_current 45
telemt_desync_total 339
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 5
telemt_pool_force_close_total 111
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 1748
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1656
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1637
telemt_me_writer_teardown_success_total{mode="normal"} 1772
telemt_me_writer_teardown_noop_total 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3520
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.210950
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3520
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 45502
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 1057496748 (1008.51 MB)
telemt_user_octets_to_client{user="hello"} 37775297244 (35.18 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 86850.8 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6446769
telemt_connections_bad_total 660104
telemt_connections_current 3399
telemt_connections_me_current 3399
telemt_handshake_timeouts_total 186604
telemt_upstream_connect_attempt_total 32916
telemt_upstream_connect_success_total 32785
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 32879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 1397
telemt_me_reconnect_success_total 703
telemt_me_reader_eof_total 678
telemt_me_idle_close_by_peer_total 678
telemt_me_route_drop_no_conn_total 1994090
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4941963
telemt_me_endpoint_quarantine_total 577
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 661
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
telemt_me_writers_active_current 45
telemt_desync_total 18798
telemt_desync_full_logged_total 6260
telemt_desync_suppressed_total 12538
telemt_desync_frames_bucket_total{bucket="1_2"} 4577
telemt_desync_frames_bucket_total{bucket="3_10"} 6852
telemt_desync_frames_bucket_total{bucket="gt_10"} 7369
telemt_pool_swap_total 96
telemt_pool_force_close_total 2624
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 329
telemt_me_draining_writers_reap_progress_total 29543
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2402
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27809
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2540
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26919
telemt_me_writer_teardown_success_total{mode="normal"} 30211
telemt_me_writer_teardown_noop_total 29545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59756
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.721896
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59756
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 329
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 628
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4917811
telemt_user_connections_current{user="hello"} 3399
telemt_user_octets_from_client{user="hello"} 97912356248 (91.19 GB)
telemt_user_octets_to_client{user="hello"} 2293629816656 (2.09 TB)
telemt_user_unique_ips_current{user="hello"} 1285
telemt_user_unique_ips_recent_window{user="hello"} 379
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 86847.4 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5466578
telemt_connections_bad_total 511094
telemt_connections_current 3209
telemt_connections_me_current 3209
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 156218
telemt_upstream_connect_attempt_total 49362
telemt_upstream_connect_success_total 48997
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 49303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_reconnect_attempts_total 4482
telemt_me_reconnect_success_total 993
telemt_me_reader_eof_total 878
telemt_me_idle_close_by_peer_total 878
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2047885
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4307111
telemt_me_endpoint_quarantine_total 688
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 659
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 17485
telemt_desync_full_logged_total 5890
telemt_desync_suppressed_total 11595
telemt_desync_frames_bucket_total{bucket="1_2"} 4326
telemt_desync_frames_bucket_total{bucket="3_10"} 6427
telemt_desync_frames_bucket_total{bucket="gt_10"} 6732
telemt_pool_swap_total 94
telemt_pool_force_close_total 2552
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 332
telemt_me_draining_writers_reap_progress_total 28813
telemt_me_writer_removed_unexpected_total 891
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2887
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26856
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26261
telemt_me_writer_teardown_success_total{mode="normal"} 29743
telemt_me_writer_teardown_noop_total 28817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58560
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.935143
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58560
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 332
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 765
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4311300
telemt_user_connections_current{user="hello"} 3209
telemt_user_octets_from_client{user="hello"} 82514839945 (76.85 GB)
telemt_user_octets_to_client{user="hello"} 1806493038928 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1242
telemt_user_unique_ips_recent_window{user="hello"} 364
```