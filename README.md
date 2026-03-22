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

# Server Metrics 2026-03-22 21:26:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 87633.5 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3208005
telemt_connections_bad_total 234532
telemt_connections_current 911
telemt_connections_me_current 911
telemt_handshake_timeouts_total 102757
telemt_upstream_connect_attempt_total 32138
telemt_upstream_connect_success_total 32137
telemt_upstream_connect_attempts_per_request{bucket="1"} 32137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1307
telemt_me_reconnect_success_total 539
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 2838620
telemt_me_route_drop_channel_closed_total 1139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2700715
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 680
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
telemt_desync_total 11669
telemt_desync_full_logged_total 3660
telemt_desync_suppressed_total 8009
telemt_desync_frames_bucket_total{bucket="1_2"} 3164
telemt_desync_frames_bucket_total{bucket="3_10"} 4260
telemt_desync_frames_bucket_total{bucket="gt_10"} 4245
telemt_pool_swap_total 97
telemt_pool_force_close_total 3020
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 29388
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2140
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27488
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2965
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26368
telemt_me_writer_teardown_success_total{mode="normal"} 29628
telemt_me_writer_teardown_noop_total 29399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59027
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 333.085052
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59027
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 479
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2690727
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 39223118504 (36.53 GB)
telemt_user_octets_to_client{user="hello"} 726980053184 (677.05 GB)
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 100999.7 (28h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3902258
telemt_connections_bad_total 345810
telemt_connections_current 641
telemt_connections_me_current 641
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99277
telemt_upstream_connect_attempt_total 60516
telemt_upstream_connect_success_total 59781
telemt_upstream_connect_fail_total 649
telemt_upstream_connect_attempts_per_request{bucket="1"} 60430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 649
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6968
telemt_me_reconnect_success_total 2707
telemt_me_reader_eof_total 2659
telemt_me_idle_close_by_peer_total 2659
telemt_me_route_drop_no_conn_total 3625242
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3111001
telemt_me_endpoint_quarantine_total 768
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 779
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 12610
telemt_desync_full_logged_total 7065
telemt_desync_suppressed_total 5545
telemt_desync_frames_bucket_total{bucket="1_2"} 2847
telemt_desync_frames_bucket_total{bucket="3_10"} 4954
telemt_desync_frames_bucket_total{bucket="gt_10"} 4809
telemt_pool_swap_total 95
telemt_pool_force_close_total 2858
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 237
telemt_me_draining_writers_reap_progress_total 40234
telemt_me_writer_removed_unexpected_total 2600
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4900
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37956
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2431
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37376
telemt_me_writer_teardown_success_total{mode="normal"} 42856
telemt_me_writer_teardown_noop_total 40235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83091
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.376133
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83091
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 237
telemt_me_refill_failed_total 171
telemt_me_writer_restored_same_endpoint_total 2385
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 3121679
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 40951248483 (38.14 GB)
telemt_user_octets_to_client{user="hello"} 762944839910 (710.55 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 175859.7 (48h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16089077
telemt_connections_bad_total 1560121
telemt_connections_current 1129
telemt_connections_me_current 1129
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 394780
telemt_upstream_connect_attempt_total 78006
telemt_upstream_connect_success_total 77906
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 77923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1693
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2842
telemt_me_reconnect_success_total 1477
telemt_me_reader_eof_total 1422
telemt_me_idle_close_by_peer_total 1420
telemt_me_route_drop_no_conn_total 14013588
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12825690
telemt_me_endpoint_quarantine_total 1124
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 52954
telemt_desync_full_logged_total 16723
telemt_desync_suppressed_total 36231
telemt_desync_frames_bucket_total{bucket="1_2"} 11772
telemt_desync_frames_bucket_total{bucket="3_10"} 20628
telemt_desync_frames_bucket_total{bucket="gt_10"} 20554
telemt_pool_swap_total 190
telemt_pool_force_close_total 6380
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1031
telemt_me_draining_writers_reap_progress_total 57983
telemt_me_writer_removed_unexpected_total 1372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5067
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51603
telemt_me_writer_teardown_success_total{mode="normal"} 58634
telemt_me_writer_teardown_noop_total 58034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116668
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 315.363154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116668
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1031
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1276
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12825990
telemt_user_connections_current{user="hello"} 1129
telemt_user_octets_from_client{user="hello"} 188476821973 (175.53 GB)
telemt_user_octets_to_client{user="hello"} 3436862090759 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 175861.0 (48h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11670883
telemt_connections_bad_total 1180656
telemt_connections_current 980
telemt_connections_me_current 980
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343474
telemt_upstream_connect_attempt_total 92542
telemt_upstream_connect_success_total 91236
telemt_upstream_connect_fail_total 860
telemt_upstream_connect_attempts_per_request{bucket="1"} 92096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 860
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4278
telemt_me_reconnect_success_total 1786
telemt_me_reader_eof_total 1645
telemt_me_idle_close_by_peer_total 1645
telemt_me_route_drop_no_conn_total 4530434
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8691361
telemt_me_endpoint_quarantine_total 1124
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1335
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38413
telemt_desync_full_logged_total 12924
telemt_desync_suppressed_total 25489
telemt_desync_frames_bucket_total{bucket="1_2"} 9487
telemt_desync_frames_bucket_total{bucket="3_10"} 14779
telemt_desync_frames_bucket_total{bucket="gt_10"} 14147
telemt_pool_swap_total 187
telemt_pool_force_close_total 5757
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 56400
telemt_me_writer_removed_unexpected_total 1682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5223
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52708
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5245
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50643
telemt_me_writer_teardown_success_total{mode="normal"} 57931
telemt_me_writer_teardown_noop_total 56425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.211886
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1519
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8629272
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 216692101144 (201.81 GB)
telemt_user_octets_to_client{user="hello"} 3907560517319 (3.55 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 175825.0 (48h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10915113
telemt_connections_bad_total 947560
telemt_connections_current 777
telemt_connections_me_current 777
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344621
telemt_upstream_connect_attempt_total 76171
telemt_upstream_connect_success_total 74787
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 74984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5388
telemt_me_reconnect_success_total 2191
telemt_me_reader_eof_total 1925
telemt_me_idle_close_by_peer_total 1924
telemt_me_route_drop_no_conn_total 5310318
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8260339
telemt_me_endpoint_quarantine_total 1211
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1289
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 66
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
telemt_me_writers_active_current 46
telemt_desync_total 37830
telemt_desync_full_logged_total 12533
telemt_desync_suppressed_total 25297
telemt_desync_frames_bucket_total{bucket="1_2"} 9559
telemt_desync_frames_bucket_total{bucket="3_10"} 14469
telemt_desync_frames_bucket_total{bucket="gt_10"} 13802
telemt_pool_swap_total 184
telemt_pool_force_close_total 5698
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 723
telemt_me_draining_writers_reap_progress_total 56520
telemt_me_writer_removed_unexpected_total 2077
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5812
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52709
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50822
telemt_me_writer_teardown_success_total{mode="normal"} 58521
telemt_me_writer_teardown_noop_total 56591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115112
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.213998
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115112
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 723
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 1891
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8252365
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 191789581965 (178.62 GB)
telemt_user_octets_to_client{user="hello"} 3433232427345 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 46105.1 (12h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10991025
telemt_connections_bad_total 666636
telemt_connections_current 1263
telemt_connections_me_current 1263
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 244838
telemt_upstream_connect_attempt_total 50216
telemt_upstream_connect_success_total 47682
telemt_upstream_connect_fail_total 1735
telemt_upstream_connect_attempts_per_request{bucket="1"} 49417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5984
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1735
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7003
telemt_me_reconnect_success_total 1023
telemt_me_reader_eof_total 633
telemt_me_idle_close_by_peer_total 632
telemt_me_route_drop_no_conn_total 25243323
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9127066
telemt_me_endpoint_quarantine_total 321
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 364
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_me_writers_active_current 41
telemt_desync_total 15385
telemt_desync_full_logged_total 4092
telemt_desync_suppressed_total 11293
telemt_desync_frames_bucket_total{bucket="1_2"} 2907
telemt_desync_frames_bucket_total{bucket="3_10"} 6247
telemt_desync_frames_bucket_total{bucket="gt_10"} 6231
telemt_pool_swap_total 47
telemt_pool_force_close_total 1665
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 13436
telemt_me_writer_removed_unexpected_total 912
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12314
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1359
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11771
telemt_me_writer_teardown_success_total{mode="normal"} 14304
telemt_me_writer_teardown_noop_total 13455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27759
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.118750
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27759
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 325
telemt_me_writer_restored_same_endpoint_total 665
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 9151788
telemt_user_connections_current{user="hello"} 1263
telemt_user_octets_from_client{user="hello"} 84966294304 (79.13 GB)
telemt_user_octets_to_client{user="hello"} 541742403022 (504.54 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 175831.7 (48h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10821801
telemt_connections_bad_total 912072
telemt_connections_current 885
telemt_connections_me_current 885
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237690
telemt_upstream_connect_attempt_total 105056
telemt_upstream_connect_success_total 103956
telemt_upstream_connect_fail_total 936
telemt_upstream_connect_attempts_per_request{bucket="1"} 104892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 936
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72532
telemt_me_reconnect_success_total 2865
telemt_me_reader_eof_total 2561
telemt_me_idle_close_by_peer_total 2559
telemt_me_route_drop_no_conn_total 5229470
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8553536
telemt_me_endpoint_quarantine_total 1161
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1318
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 45624
telemt_desync_full_logged_total 15580
telemt_desync_suppressed_total 30044
telemt_desync_frames_bucket_total{bucket="1_2"} 9254
telemt_desync_frames_bucket_total{bucket="3_10"} 17468
telemt_desync_frames_bucket_total{bucket="gt_10"} 18902
telemt_pool_swap_total 180
telemt_pool_force_close_total 5371
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 646
telemt_me_draining_writers_reap_progress_total 60386
telemt_me_writer_removed_unexpected_total 2596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6366
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56645
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4641
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55015
telemt_me_writer_teardown_success_total{mode="normal"} 63011
telemt_me_writer_teardown_noop_total 60387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123398
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.138881
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123398
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 646
telemt_me_refill_failed_total 4291
telemt_me_writer_restored_same_endpoint_total 2411
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8556652
telemt_user_connections_current{user="hello"} 885
telemt_user_octets_from_client{user="hello"} 193288832413 (180.01 GB)
telemt_user_octets_to_client{user="hello"} 3261190435636 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 112667.9 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11440320
telemt_connections_bad_total 457414
telemt_connections_current 1129
telemt_connections_me_current 1129
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4688071
telemt_upstream_connect_attempt_total 53232
telemt_upstream_connect_success_total 52837
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 53222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_reconnect_attempts_total 48658
telemt_me_reconnect_success_total 1699
telemt_me_reader_eof_total 1360
telemt_me_idle_close_by_peer_total 1359
telemt_me_route_drop_no_conn_total 4062362
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5518932
telemt_me_endpoint_quarantine_total 735
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 851
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30987
telemt_desync_full_logged_total 10536
telemt_desync_suppressed_total 20451
telemt_desync_frames_bucket_total{bucket="1_2"} 6158
telemt_desync_frames_bucket_total{bucket="3_10"} 12257
telemt_desync_frames_bucket_total{bucket="gt_10"} 12572
telemt_pool_swap_total 119
telemt_pool_force_close_total 3591
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 39408
telemt_me_writer_removed_unexpected_total 1418
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37437
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3150
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35817
telemt_me_writer_teardown_success_total{mode="normal"} 40862
telemt_me_writer_teardown_noop_total 39415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80277
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.616445
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80277
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1509
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5511629
telemt_user_connections_current{user="hello"} 1129
telemt_user_octets_from_client{user="hello"} 118157290784 (110.04 GB)
telemt_user_octets_to_client{user="hello"} 2114833436898 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 93638.4 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1417776
telemt_connections_bad_total 35180
telemt_connections_current 836
telemt_connections_me_current 836
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26565
telemt_upstream_connect_attempt_total 43873
telemt_upstream_connect_success_total 43736
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 43846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 752
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2048
telemt_me_reconnect_success_total 833
telemt_me_reader_eof_total 815
telemt_me_idle_close_by_peer_total 815
telemt_me_route_drop_no_conn_total 493161
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1258117
telemt_me_endpoint_quarantine_total 759
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 769
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_warm_current 10
telemt_desync_total 7805
telemt_desync_full_logged_total 2384
telemt_desync_suppressed_total 5421
telemt_desync_frames_bucket_total{bucket="1_2"} 1859
telemt_desync_frames_bucket_total{bucket="3_10"} 3010
telemt_desync_frames_bucket_total{bucket="gt_10"} 2936
telemt_pool_swap_total 100
telemt_pool_force_close_total 2603
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 36640
telemt_me_writer_removed_unexpected_total 785
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2890
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34568
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2516
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34037
telemt_me_writer_teardown_success_total{mode="normal"} 37458
telemt_me_writer_teardown_noop_total 36644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74102
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.831392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74102
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 707
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1254100
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 24406532681 (22.73 GB)
telemt_user_octets_to_client{user="hello"} 530815735983 (494.36 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 175836.2 (48h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13155379
telemt_connections_bad_total 1556572
telemt_connections_current 1042
telemt_connections_me_current 1042
telemt_handshake_timeouts_total 377490
telemt_upstream_connect_attempt_total 66885
telemt_upstream_connect_success_total 66549
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 66749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2625
telemt_me_reconnect_success_total 1366
telemt_me_reader_eof_total 1334
telemt_me_idle_close_by_peer_total 1334
telemt_me_route_drop_no_conn_total 4460050
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9944050
telemt_me_endpoint_quarantine_total 1197
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1317
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
telemt_me_writers_active_current 43
telemt_desync_total 41487
telemt_desync_full_logged_total 13528
telemt_desync_suppressed_total 27959
telemt_desync_frames_bucket_total{bucket="1_2"} 9977
telemt_desync_frames_bucket_total{bucket="3_10"} 15276
telemt_desync_frames_bucket_total{bucket="gt_10"} 16234
telemt_pool_swap_total 195
telemt_pool_force_close_total 5337
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 657
telemt_me_draining_writers_reap_progress_total 60319
telemt_me_writer_removed_unexpected_total 1283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4895
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56748
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5163
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54982
telemt_me_writer_teardown_success_total{mode="normal"} 61643
telemt_me_writer_teardown_noop_total 60321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121964
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.544821
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121964
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 657
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 9910924
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 193611086064 (180.31 GB)
telemt_user_octets_to_client{user="hello"} 4385100093924 (3.99 TB)
telemt_user_unique_ips_current{user="hello"} 389
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 175832.9 (48h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11436314
telemt_connections_bad_total 1296363
telemt_connections_current 1086
telemt_connections_me_current 1086
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 301491
telemt_upstream_connect_attempt_total 93308
telemt_upstream_connect_success_total 92471
telemt_upstream_connect_fail_total 630
telemt_upstream_connect_attempts_per_request{bucket="1"} 93101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 630
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9980
telemt_me_reconnect_success_total 2406
telemt_me_reader_eof_total 2249
telemt_me_idle_close_by_peer_total 2248
telemt_me_seq_mismatch_total 81
telemt_me_route_drop_no_conn_total 5619555
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8845457
telemt_me_endpoint_quarantine_total 1349
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1321
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
telemt_me_writers_active_current 46
telemt_desync_total 40939
telemt_desync_full_logged_total 13132
telemt_desync_suppressed_total 27807
telemt_desync_frames_bucket_total{bucket="1_2"} 10454
telemt_desync_frames_bucket_total{bucket="3_10"} 15099
telemt_desync_frames_bucket_total{bucket="gt_10"} 15386
telemt_pool_swap_total 185
telemt_pool_force_close_total 5133
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 60057
telemt_me_writer_removed_unexpected_total 2281
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56188
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54924
telemt_me_writer_teardown_success_total{mode="normal"} 62416
telemt_me_writer_teardown_noop_total 60062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122478
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.264570
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122478
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 391
telemt_me_writer_restored_same_endpoint_total 1957
telemt_me_writer_restored_fallback_total 113
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 8850921
telemt_user_connections_current{user="hello"} 1086
telemt_user_octets_from_client{user="hello"} 156416217357 (145.67 GB)
telemt_user_octets_to_client{user="hello"} 3440398372599 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 389
telemt_user_unique_ips_recent_window{user="hello"} 111
```