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

# Server Metrics 2026-03-23 01:26:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 101990.1 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3536900
telemt_connections_bad_total 315023
telemt_connections_current 827
telemt_connections_me_current 827
telemt_handshake_timeouts_total 110448
telemt_upstream_connect_attempt_total 37946
telemt_upstream_connect_success_total 37945
telemt_upstream_connect_attempts_per_request{bucket="1"} 37945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1399
telemt_me_reconnect_success_total 605
telemt_me_reader_eof_total 622
telemt_me_idle_close_by_peer_total 622
telemt_me_route_drop_no_conn_total 2987168
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2917644
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 796
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
telemt_desync_total 12549
telemt_desync_full_logged_total 3943
telemt_desync_suppressed_total 8606
telemt_desync_frames_bucket_total{bucket="1_2"} 3374
telemt_desync_frames_bucket_total{bucket="3_10"} 4571
telemt_desync_frames_bucket_total{bucket="gt_10"} 4604
telemt_pool_swap_total 113
telemt_pool_force_close_total 3482
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 34756
telemt_me_writer_removed_unexpected_total 599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2495
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3426
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31274
telemt_me_writer_teardown_success_total{mode="normal"} 35004
telemt_me_writer_teardown_noop_total 34767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69771
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.682054
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69771
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 541
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2906689
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 41542234060 (38.69 GB)
telemt_user_octets_to_client{user="hello"} 796089654040 (741.42 GB)
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 115356.1 (32h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4005142
telemt_connections_bad_total 369387
telemt_connections_current 416
telemt_connections_me_current 416
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100797
telemt_upstream_connect_attempt_total 72002
telemt_upstream_connect_success_total 71144
telemt_upstream_connect_fail_total 765
telemt_upstream_connect_attempts_per_request{bucket="1"} 71909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 765
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10138
telemt_me_reconnect_success_total 3633
telemt_me_reader_eof_total 3628
telemt_me_idle_close_by_peer_total 3628
telemt_me_route_drop_no_conn_total 3641425
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3181775
telemt_me_endpoint_quarantine_total 922
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 898
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 41
telemt_desync_total 12968
telemt_desync_full_logged_total 7272
telemt_desync_suppressed_total 5696
telemt_desync_frames_bucket_total{bucket="1_2"} 2941
telemt_desync_frames_bucket_total{bucket="3_10"} 5085
telemt_desync_frames_bucket_total{bucket="gt_10"} 4942
telemt_pool_swap_total 108
telemt_pool_force_close_total 3071
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 47492
telemt_me_writer_removed_unexpected_total 3558
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6241
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44842
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2613
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44421
telemt_me_writer_teardown_success_total{mode="normal"} 51083
telemt_me_writer_teardown_noop_total 47493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.621952
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 3243
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 3195076
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 43084440687 (40.13 GB)
telemt_user_octets_to_client{user="hello"} 792327444072 (737.91 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 190215.9 (52h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16351031
telemt_connections_bad_total 1655815
telemt_connections_current 770
telemt_connections_me_current 770
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397619
telemt_upstream_connect_attempt_total 85328
telemt_upstream_connect_success_total 85223
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 85240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1717
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3009
telemt_me_reconnect_success_total 1583
telemt_me_reader_eof_total 1531
telemt_me_idle_close_by_peer_total 1529
telemt_me_route_drop_no_conn_total 14047289
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12982827
telemt_me_endpoint_quarantine_total 1270
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1434
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_active_current 45
telemt_desync_total 53875
telemt_desync_full_logged_total 17110
telemt_desync_suppressed_total 36765
telemt_desync_frames_bucket_total{bucket="1_2"} 12010
telemt_desync_frames_bucket_total{bucket="3_10"} 21025
telemt_desync_frames_bucket_total{bucket="gt_10"} 20840
telemt_pool_swap_total 206
telemt_pool_force_close_total 6740
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1064
telemt_me_draining_writers_reap_progress_total 64716
telemt_me_writer_removed_unexpected_total 1473
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5520
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59946
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6270
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57976
telemt_me_writer_teardown_success_total{mode="normal"} 65466
telemt_me_writer_teardown_noop_total 64769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130235
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.790849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130235
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1064
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1370
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12982849
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 191204672425 (178.07 GB)
telemt_user_octets_to_client{user="hello"} 3490574468075 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 190217.4 (52h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11888971
telemt_connections_bad_total 1237405
telemt_connections_current 540
telemt_connections_me_current 540
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344625
telemt_upstream_connect_attempt_total 99684
telemt_upstream_connect_success_total 98356
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 99231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41608
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4440
telemt_me_reconnect_success_total 1890
telemt_me_reader_eof_total 1757
telemt_me_idle_close_by_peer_total 1757
telemt_me_route_drop_no_conn_total 4557211
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8825257
telemt_me_endpoint_quarantine_total 1273
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1453
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 45
telemt_desync_total 38863
telemt_desync_full_logged_total 13077
telemt_desync_suppressed_total 25786
telemt_desync_frames_bucket_total{bucket="1_2"} 9628
telemt_desync_frames_bucket_total{bucket="3_10"} 14926
telemt_desync_frames_bucket_total{bucket="gt_10"} 14309
telemt_pool_swap_total 203
telemt_pool_force_close_total 6100
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 62924
telemt_me_writer_removed_unexpected_total 1786
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5609
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58958
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5588
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56824
telemt_me_writer_teardown_success_total{mode="normal"} 64567
telemt_me_writer_teardown_noop_total 62949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127516
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.438770
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127516
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1617
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8763015
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 217838581336 (202.88 GB)
telemt_user_octets_to_client{user="hello"} 3964652799139 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 190181.3 (52h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11064870
telemt_connections_bad_total 976107
telemt_connections_current 435
telemt_connections_me_current 435
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345618
telemt_upstream_connect_attempt_total 83960
telemt_upstream_connect_success_total 82401
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 82606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5757
telemt_me_reconnect_success_total 2379
telemt_me_reader_eof_total 2124
telemt_me_idle_close_by_peer_total 2123
telemt_me_route_drop_no_conn_total 5338398
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8363126
telemt_me_endpoint_quarantine_total 1339
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1408
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_me_writers_active_current 43
telemt_desync_total 38187
telemt_desync_full_logged_total 12643
telemt_desync_suppressed_total 25544
telemt_desync_frames_bucket_total{bucket="1_2"} 9643
telemt_desync_frames_bucket_total{bucket="3_10"} 14611
telemt_desync_frames_bucket_total{bucket="gt_10"} 13933
telemt_pool_swap_total 199
telemt_pool_force_close_total 6000
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 741
telemt_me_draining_writers_reap_progress_total 63295
telemt_me_writer_removed_unexpected_total 2274
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6359
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59142
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5429
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57295
telemt_me_writer_teardown_success_total{mode="normal"} 65501
telemt_me_writer_teardown_noop_total 63366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128867
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.797651
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128867
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 741
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2069
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8355082
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 192787633003 (179.55 GB)
telemt_user_octets_to_client{user="hello"} 3472232461009 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 60461.7 (16h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11261512
telemt_connections_bad_total 669192
telemt_connections_current 952
telemt_connections_me_current 952
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 274232
telemt_upstream_connect_attempt_total 58437
telemt_upstream_connect_success_total 55366
telemt_upstream_connect_fail_total 2033
telemt_upstream_connect_attempts_per_request{bucket="1"} 57399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6017
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2033
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7772
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 792
telemt_me_idle_close_by_peer_total 791
telemt_me_route_drop_no_conn_total 25292261
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9342293
telemt_me_endpoint_quarantine_total 454
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 484
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 16358
telemt_desync_full_logged_total 4466
telemt_desync_suppressed_total 11892
telemt_desync_frames_bucket_total{bucket="1_2"} 3100
telemt_desync_frames_bucket_total{bucket="3_10"} 6665
telemt_desync_frames_bucket_total{bucket="gt_10"} 6593
telemt_pool_swap_total 63
telemt_pool_force_close_total 2020
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 18999
telemt_me_writer_removed_unexpected_total 1148
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2577
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17514
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1713
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16979
telemt_me_writer_teardown_success_total{mode="normal"} 20091
telemt_me_writer_teardown_noop_total 19018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39109
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.892279
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39109
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 339
telemt_me_writer_restored_same_endpoint_total 809
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 9368172
telemt_user_connections_current{user="hello"} 952
telemt_user_octets_from_client{user="hello"} 87431574650 (81.43 GB)
telemt_user_octets_to_client{user="hello"} 611772047302 (569.76 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 190187.9 (52h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11006087
telemt_connections_bad_total 951895
telemt_connections_current 502
telemt_connections_me_current 502
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242340
telemt_upstream_connect_attempt_total 112842
telemt_upstream_connect_success_total 111679
telemt_upstream_connect_fail_total 989
telemt_upstream_connect_attempts_per_request{bucket="1"} 112668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 989
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72982
telemt_me_reconnect_success_total 3089
telemt_me_reader_eof_total 2780
telemt_me_idle_close_by_peer_total 2778
telemt_me_route_drop_no_conn_total 5264502
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8683242
telemt_me_endpoint_quarantine_total 1285
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1438
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 42
telemt_desync_total 46276
telemt_desync_full_logged_total 15858
telemt_desync_suppressed_total 30418
telemt_desync_frames_bucket_total{bucket="1_2"} 9403
telemt_desync_frames_bucket_total{bucket="3_10"} 17714
telemt_desync_frames_bucket_total{bucket="gt_10"} 19159
telemt_pool_swap_total 195
telemt_pool_force_close_total 5712
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67435
telemt_me_writer_removed_unexpected_total 2807
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6879
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63400
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4963
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61723
telemt_me_writer_teardown_success_total{mode="normal"} 70279
telemt_me_writer_teardown_noop_total 67436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137715
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.278635
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137715
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 4302
telemt_me_writer_restored_same_endpoint_total 2605
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8686211
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 194705068841 (181.33 GB)
telemt_user_octets_to_client{user="hello"} 3320501409964 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 127024.3 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11709539
telemt_connections_bad_total 482531
telemt_connections_current 679
telemt_connections_me_current 679
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4762149
telemt_upstream_connect_attempt_total 61215
telemt_upstream_connect_success_total 60767
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 61204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_reconnect_attempts_total 49006
telemt_me_reconnect_success_total 1823
telemt_me_reader_eof_total 1496
telemt_me_idle_close_by_peer_total 1495
telemt_me_route_drop_no_conn_total 4094355
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5626883
telemt_me_endpoint_quarantine_total 865
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 972
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31650
telemt_desync_full_logged_total 10799
telemt_desync_suppressed_total 20851
telemt_desync_frames_bucket_total{bucket="1_2"} 6297
telemt_desync_frames_bucket_total{bucket="3_10"} 12482
telemt_desync_frames_bucket_total{bucket="gt_10"} 12871
telemt_pool_swap_total 135
telemt_pool_force_close_total 3907
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 46723
telemt_me_writer_removed_unexpected_total 1547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3819
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44494
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3466
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42816
telemt_me_writer_teardown_success_total{mode="normal"} 48313
telemt_me_writer_teardown_noop_total 46730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95043
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.694183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95043
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 2741
telemt_me_writer_restored_same_endpoint_total 1614
telemt_me_writer_restored_fallback_total 28
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5619038
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 119139368300 (110.96 GB)
telemt_user_octets_to_client{user="hello"} 2181784822890 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 107995.0 (29h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1529622
telemt_connections_bad_total 36773
telemt_connections_current 453
telemt_connections_me_current 453
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31071
telemt_upstream_connect_attempt_total 50913
telemt_upstream_connect_success_total 50755
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 50885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 791
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2258
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 909
telemt_me_idle_close_by_peer_total 909
telemt_me_route_drop_no_conn_total 518795
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1359551
telemt_me_endpoint_quarantine_total 893
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 891
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 9077
telemt_desync_full_logged_total 2639
telemt_desync_suppressed_total 6438
telemt_desync_frames_bucket_total{bucket="1_2"} 2574
telemt_desync_frames_bucket_total{bucket="3_10"} 3459
telemt_desync_frames_bucket_total{bucket="gt_10"} 3044
telemt_pool_swap_total 116
telemt_pool_force_close_total 2961
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 168
telemt_me_draining_writers_reap_progress_total 43083
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3288
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40711
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2873
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40122
telemt_me_writer_teardown_success_total{mode="normal"} 43999
telemt_me_writer_teardown_noop_total 43087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87086
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.316564
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87086
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 168
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 785
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1355365
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 26079001757 (24.29 GB)
telemt_user_octets_to_client{user="hello"} 576348167151 (536.77 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 190192.6 (52h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13332899
telemt_connections_bad_total 1602331
telemt_connections_current 603
telemt_connections_me_current 603
telemt_handshake_timeouts_total 389210
telemt_upstream_connect_attempt_total 75060
telemt_upstream_connect_success_total 74708
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 74924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2999
telemt_me_reconnect_success_total 1498
telemt_me_reader_eof_total 1483
telemt_me_idle_close_by_peer_total 1483
telemt_me_route_drop_no_conn_total 4484060
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10054577
telemt_me_endpoint_quarantine_total 1370
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1440
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 43
telemt_desync_total 42108
telemt_desync_full_logged_total 13753
telemt_desync_suppressed_total 28355
telemt_desync_frames_bucket_total{bucket="1_2"} 10193
telemt_desync_frames_bucket_total{bucket="3_10"} 15478
telemt_desync_frames_bucket_total{bucket="gt_10"} 16437
telemt_pool_swap_total 211
telemt_pool_force_close_total 5611
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 679
telemt_me_draining_writers_reap_progress_total 67865
telemt_me_writer_removed_unexpected_total 1421
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5345
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63993
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5437
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62254
telemt_me_writer_teardown_success_total{mode="normal"} 69338
telemt_me_writer_teardown_noop_total 67867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137205
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.793531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137205
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 679
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 1315
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 10021280
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 194831561672 (181.45 GB)
telemt_user_octets_to_client{user="hello"} 4441393820380 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 190189.0 (52h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11650911
telemt_connections_bad_total 1362873
telemt_connections_current 507
telemt_connections_me_current 507
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311767
telemt_upstream_connect_attempt_total 102540
telemt_upstream_connect_success_total 101651
telemt_upstream_connect_fail_total 681
telemt_upstream_connect_attempts_per_request{bucket="1"} 102332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 681
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10481
telemt_me_reconnect_success_total 2588
telemt_me_reader_eof_total 2401
telemt_me_idle_close_by_peer_total 2400
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5651412
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8965393
telemt_me_endpoint_quarantine_total 1544
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1442
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 41819
telemt_desync_full_logged_total 13461
telemt_desync_suppressed_total 28358
telemt_desync_frames_bucket_total{bucket="1_2"} 10804
telemt_desync_frames_bucket_total{bucket="3_10"} 15380
telemt_desync_frames_bucket_total{bucket="gt_10"} 15635
telemt_pool_swap_total 201
telemt_pool_force_close_total 5387
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 67891
telemt_me_writer_removed_unexpected_total 2442
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6696
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63722
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62504
telemt_me_writer_teardown_success_total{mode="normal"} 70418
telemt_me_writer_teardown_noop_total 67896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138314
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.478001
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138314
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2084
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8969978
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 157413285820 (146.60 GB)
telemt_user_octets_to_client{user="hello"} 3491528731574 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 57
```