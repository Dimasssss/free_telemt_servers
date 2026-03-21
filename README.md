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

# Server Metrics 2026-03-21 20:23:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 85655.6 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3061311
telemt_connections_bad_total 178998
telemt_connections_current 998
telemt_connections_me_current 998
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 94156
telemt_upstream_connect_attempt_total 35030
telemt_upstream_connect_success_total 34884
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 34987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1887
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 2619112
telemt_me_route_drop_channel_closed_total 843
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2476813
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 584
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 667
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 9893
telemt_desync_full_logged_total 3450
telemt_desync_suppressed_total 6443
telemt_desync_frames_bucket_total{bucket="1_2"} 2156
telemt_desync_frames_bucket_total{bucket="3_10"} 3724
telemt_desync_frames_bucket_total{bucket="gt_10"} 4013
telemt_pool_swap_total 93
telemt_pool_force_close_total 2788
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 642
telemt_me_draining_writers_reap_progress_total 28681
telemt_me_writer_removed_unexpected_total 710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2417
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26714
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25893
telemt_me_writer_teardown_success_total{mode="normal"} 29131
telemt_me_writer_teardown_noop_total 28689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57820
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 297.989484
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57820
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 642
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 653
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 2476463
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 36718186949 (34.20 GB)
telemt_user_octets_to_client{user="hello"} 629278753890 (586.06 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 10793.4 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438011
telemt_connections_bad_total 20044
telemt_connections_current 1467
telemt_connections_me_current 1467
telemt_handshake_timeouts_total 15385
telemt_upstream_connect_attempt_total 4275
telemt_upstream_connect_success_total 4187
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 4263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 220
telemt_me_reconnect_success_total 136
telemt_me_reader_eof_total 112
telemt_me_idle_close_by_peer_total 112
telemt_me_route_drop_no_conn_total 266325
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357148
telemt_me_endpoint_quarantine_total 79
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 1519
telemt_desync_full_logged_total 859
telemt_desync_suppressed_total 660
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 575
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 11
telemt_pool_force_close_total 335
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 3703
telemt_me_writer_removed_unexpected_total 106
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3489
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 328
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3368
telemt_me_writer_teardown_success_total{mode="normal"} 3802
telemt_me_writer_teardown_noop_total 3703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7505
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.039598
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7505
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 94
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 356753
telemt_user_connections_current{user="hello"} 1467
telemt_user_octets_from_client{user="hello"} 5697823304 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 103863598464 (96.73 GB)
telemt_user_unique_ips_current{user="hello"} 876
telemt_user_unique_ips_recent_window{user="hello"} 304
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 85653.4 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6815259
telemt_connections_bad_total 526629
telemt_connections_current 4155
telemt_connections_me_current 4155
telemt_handshake_timeouts_total 213311
telemt_upstream_connect_attempt_total 30799
telemt_upstream_connect_success_total 30737
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 30743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1325
telemt_me_reconnect_success_total 666
telemt_me_reader_eof_total 675
telemt_me_idle_close_by_peer_total 675
telemt_me_route_drop_no_conn_total 4334514
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5585645
telemt_me_endpoint_quarantine_total 532
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 635
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 22939
telemt_desync_full_logged_total 7639
telemt_desync_suppressed_total 15300
telemt_desync_frames_bucket_total{bucket="1_2"} 4795
telemt_desync_frames_bucket_total{bucket="3_10"} 9127
telemt_desync_frames_bucket_total{bucket="gt_10"} 9017
telemt_pool_swap_total 92
telemt_pool_force_close_total 3043
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 496
telemt_me_draining_writers_reap_progress_total 27986
telemt_me_writer_removed_unexpected_total 649
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2412
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2813
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24943
telemt_me_writer_teardown_success_total{mode="normal"} 28286
telemt_me_writer_teardown_noop_total 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56309
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 135.191044
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56309
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 496
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 597
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 5578966
telemt_user_connections_current{user="hello"} 4155
telemt_user_octets_from_client{user="hello"} 93267601400 (86.86 GB)
telemt_user_octets_to_client{user="hello"} 1749041460888 (1.59 TB)
telemt_user_unique_ips_current{user="hello"} 1732
telemt_user_unique_ips_recent_window{user="hello"} 445
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 85654.7 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5516492
telemt_connections_bad_total 536083
telemt_connections_current 3567
telemt_connections_me_current 3567
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 181855
telemt_upstream_connect_attempt_total 34923
telemt_upstream_connect_success_total 34605
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 34769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1665
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 1912885
telemt_me_route_drop_channel_closed_total 219
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4128554
telemt_me_endpoint_quarantine_total 527
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 653
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
telemt_me_writers_active_current 42
telemt_desync_total 19577
telemt_desync_full_logged_total 6468
telemt_desync_suppressed_total 13109
telemt_desync_frames_bucket_total{bucket="1_2"} 4790
telemt_desync_frames_bucket_total{bucket="3_10"} 7584
telemt_desync_frames_bucket_total{bucket="gt_10"} 7203
telemt_pool_swap_total 94
telemt_pool_force_close_total 2822
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 318
telemt_me_draining_writers_reap_progress_total 26813
telemt_me_writer_removed_unexpected_total 645
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2335
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25052
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2628
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23991
telemt_me_writer_teardown_success_total{mode="normal"} 27387
telemt_me_writer_teardown_noop_total 26818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54205
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.023473
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54205
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 318
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4122100
telemt_user_connections_current{user="hello"} 3568
telemt_user_octets_from_client{user="hello"} 124416835485 (115.87 GB)
telemt_user_octets_to_client{user="hello"} 1881483019819 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1460
telemt_user_unique_ips_recent_window{user="hello"} 429
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 85618.7 (23h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5441640
telemt_connections_bad_total 495736
telemt_connections_current 3095
telemt_connections_me_current 3095
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 165136
telemt_upstream_connect_attempt_total 41300
telemt_upstream_connect_success_total 41033
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 41168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1036
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1715
telemt_me_reconnect_success_total 750
telemt_me_reader_eof_total 694
telemt_me_idle_close_by_peer_total 694
telemt_me_route_drop_no_conn_total 1968884
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4110513
telemt_me_endpoint_quarantine_total 578
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 637
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
telemt_me_writers_active_current 43
telemt_desync_total 19354
telemt_desync_full_logged_total 6330
telemt_desync_suppressed_total 13024
telemt_desync_frames_bucket_total{bucket="1_2"} 4795
telemt_desync_frames_bucket_total{bucket="3_10"} 7344
telemt_desync_frames_bucket_total{bucket="gt_10"} 7215
telemt_pool_swap_total 92
telemt_pool_force_close_total 2684
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 332
telemt_me_draining_writers_reap_progress_total 28201
telemt_me_writer_removed_unexpected_total 664
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2410
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26476
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2472
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 212
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25517
telemt_me_writer_teardown_success_total{mode="normal"} 28886
telemt_me_writer_teardown_noop_total 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57097
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.104931
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57097
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 332
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 646
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4112767
telemt_user_connections_current{user="hello"} 3095
telemt_user_octets_from_client{user="hello"} 120320577187 (112.06 GB)
telemt_user_octets_to_client{user="hello"} 1876468929175 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1254
telemt_user_unique_ips_recent_window{user="hello"} 402
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 85658.2 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18892960
telemt_connections_bad_total 1212091
telemt_connections_current 4146
telemt_connections_me_current 4146
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 528257
telemt_upstream_connect_attempt_total 174430
telemt_upstream_connect_success_total 157547
telemt_upstream_connect_fail_total 15499
telemt_upstream_connect_attempts_per_request{bucket="1"} 173046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8823
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15499
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59398
telemt_me_reconnect_success_total 1767
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1189
telemt_me_route_drop_no_conn_total 38644818
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15553558
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 635
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 220
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 220
telemt_me_single_endpoint_shadow_rotate_total 666
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 28945
telemt_desync_full_logged_total 8537
telemt_desync_suppressed_total 20408
telemt_desync_frames_bucket_total{bucket="1_2"} 6294
telemt_desync_frames_bucket_total{bucket="3_10"} 12834
telemt_desync_frames_bucket_total{bucket="gt_10"} 9817
telemt_pool_swap_total 88
telemt_pool_force_close_total 2915
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 663
telemt_me_draining_writers_reap_progress_total 26387
telemt_me_writer_removed_unexpected_total 1657
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3529
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24257
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2458
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 457
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23472
telemt_me_writer_teardown_success_total{mode="normal"} 27786
telemt_me_writer_teardown_noop_total 26410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54196
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 200.925141
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54196
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 663
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1224
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 11365
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 15672933
telemt_user_connections_current{user="hello"} 4146
telemt_user_octets_from_client{user="hello"} 146354249091 (136.30 GB)
telemt_user_octets_to_client{user="hello"} 957430581639 (891.68 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1582
telemt_user_unique_ips_recent_window{user="hello"} 687
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 85625.7 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5354291
telemt_connections_bad_total 516745
telemt_connections_current 3045
telemt_connections_me_current 3045
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 110687
telemt_upstream_connect_attempt_total 44447
telemt_upstream_connect_success_total 43963
telemt_upstream_connect_fail_total 400
telemt_upstream_connect_attempts_per_request{bucket="1"} 44363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 400
telemt_me_reconnect_attempts_total 11061
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 1193
telemt_me_idle_close_by_peer_total 1193
telemt_me_route_drop_no_conn_total 2245351
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4154340
telemt_me_endpoint_quarantine_total 528
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 635
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
telemt_me_writers_active_current 42
telemt_desync_total 20530
telemt_desync_full_logged_total 7133
telemt_desync_suppressed_total 13397
telemt_desync_frames_bucket_total{bucket="1_2"} 3940
telemt_desync_frames_bucket_total{bucket="3_10"} 8022
telemt_desync_frames_bucket_total{bucket="gt_10"} 8568
telemt_pool_swap_total 87
telemt_pool_force_close_total 2545
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 316
telemt_me_draining_writers_reap_progress_total 29042
telemt_me_writer_removed_unexpected_total 1173
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2965
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27263
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26497
telemt_me_writer_teardown_success_total{mode="normal"} 30228
telemt_me_writer_teardown_noop_total 29043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59271
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.957049
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59271
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 316
telemt_me_refill_failed_total 591
telemt_me_writer_restored_same_endpoint_total 1068
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4144429
telemt_user_connections_current{user="hello"} 3045
telemt_user_octets_from_client{user="hello"} 110170988581 (102.60 GB)
telemt_user_octets_to_client{user="hello"} 1676067873363 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1234
telemt_user_unique_ips_recent_window{user="hello"} 443
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 22461.5 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3022995
telemt_connections_bad_total 113448
telemt_connections_current 3086
telemt_connections_me_current 3086
telemt_handshake_timeouts_total 1300004
telemt_upstream_connect_attempt_total 7256
telemt_upstream_connect_success_total 7154
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 7250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_reconnect_attempts_total 2193
telemt_me_reconnect_success_total 252
telemt_me_reader_eof_total 193
telemt_me_idle_close_by_peer_total 193
telemt_me_route_drop_no_conn_total 890632
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1433528
telemt_me_endpoint_quarantine_total 113
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 166
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
telemt_me_writers_active_current 67
telemt_desync_total 7906
telemt_desync_full_logged_total 2602
telemt_desync_suppressed_total 5304
telemt_desync_frames_bucket_total{bucket="1_2"} 1414
telemt_desync_frames_bucket_total{bucket="3_10"} 2977
telemt_desync_frames_bucket_total{bucket="gt_10"} 3515
telemt_pool_swap_total 23
telemt_pool_force_close_total 738
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 6280
telemt_me_writer_removed_unexpected_total 212
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 602
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5896
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 89
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5542
telemt_me_writer_teardown_success_total{mode="normal"} 6498
telemt_me_writer_teardown_noop_total 6280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12778
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.967613
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12778
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1429418
telemt_user_connections_current{user="hello"} 3086
telemt_user_octets_from_client{user="hello"} 43356718788 (40.38 GB)
telemt_user_octets_to_client{user="hello"} 586418410172 (546.14 GB)
telemt_user_unique_ips_current{user="hello"} 1314
telemt_user_unique_ips_recent_window{user="hello"} 409
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 3432.7 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36892
telemt_connections_bad_total 132
telemt_connections_current 673
telemt_connections_me_current 673
telemt_handshake_timeouts_total 709
telemt_upstream_connect_attempt_total 1489
telemt_upstream_connect_success_total 1484
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 48
telemt_me_reconnect_success_total 18
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 10887
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34430
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_shadow_rotate_total 31
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
telemt_desync_total 225
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 1255
telemt_me_writer_removed_unexpected_total 18
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1168
telemt_me_writer_teardown_success_total{mode="normal"} 1273
telemt_me_writer_teardown_noop_total 1255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2528
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.194748
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2528
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 15
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 34373
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 939859748 (896.32 MB)
telemt_user_octets_to_client{user="hello"} 28698767668 (26.73 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 85629.9 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6352486
telemt_connections_bad_total 654822
telemt_connections_current 4102
telemt_connections_me_current 4102
telemt_handshake_timeouts_total 184531
telemt_upstream_connect_attempt_total 32550
telemt_upstream_connect_success_total 32419
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 32513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 1391
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 673
telemt_me_idle_close_by_peer_total 673
telemt_me_route_drop_no_conn_total 1967671
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4871542
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 650
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
telemt_me_writers_active_current 42
telemt_desync_total 18413
telemt_desync_full_logged_total 6109
telemt_desync_suppressed_total 12304
telemt_desync_frames_bucket_total{bucket="1_2"} 4495
telemt_desync_frames_bucket_total{bucket="3_10"} 6732
telemt_desync_frames_bucket_total{bucket="gt_10"} 7186
telemt_pool_swap_total 95
telemt_pool_force_close_total 2565
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 322
telemt_me_draining_writers_reap_progress_total 29196
telemt_me_writer_removed_unexpected_total 656
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2373
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27486
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26631
telemt_me_writer_teardown_success_total{mode="normal"} 29859
telemt_me_writer_teardown_noop_total 29198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59057
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.506183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59057
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 322
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4847638
telemt_user_connections_current{user="hello"} 4102
telemt_user_octets_from_client{user="hello"} 96571707400 (89.94 GB)
telemt_user_octets_to_client{user="hello"} 2250898651768 (2.05 TB)
telemt_user_unique_ips_current{user="hello"} 1564
telemt_user_unique_ips_recent_window{user="hello"} 536
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 85626.6 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5373849
telemt_connections_bad_total 502477
telemt_connections_current 3102
telemt_connections_me_current 3102
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 154360
telemt_upstream_connect_attempt_total 48947
telemt_upstream_connect_success_total 48585
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 48888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 4476
telemt_me_reconnect_success_total 986
telemt_me_reader_eof_total 873
telemt_me_idle_close_by_peer_total 873
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 2017518
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4239550
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 650
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
telemt_desync_total 17134
telemt_desync_full_logged_total 5783
telemt_desync_suppressed_total 11351
telemt_desync_frames_bucket_total{bucket="1_2"} 4240
telemt_desync_frames_bucket_total{bucket="3_10"} 6291
telemt_desync_frames_bucket_total{bucket="gt_10"} 6603
telemt_pool_swap_total 93
telemt_pool_force_close_total 2491
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 323
telemt_me_draining_writers_reap_progress_total 28412
telemt_me_writer_removed_unexpected_total 885
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2847
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26489
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2298
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25921
telemt_me_writer_teardown_success_total{mode="normal"} 29336
telemt_me_writer_teardown_noop_total 28414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57750
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.369312
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57750
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 323
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 760
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4244331
telemt_user_connections_current{user="hello"} 3102
telemt_user_octets_from_client{user="hello"} 81024392741 (75.46 GB)
telemt_user_octets_to_client{user="hello"} 1774290561288 (1.61 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1178
telemt_user_unique_ips_recent_window{user="hello"} 580
```